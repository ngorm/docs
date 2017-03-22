
# Getting started

NGORM is a fork of gorm. I initially forked gorm for the purpose of improving
performance, after navigating through the whole code base it dawned to me that
there was no straight way to benchmark and any efforts won't be conveying the
truth about what is happening.

Queries are executed using `database/sql` package, majority of the time is spent
generating the queries from models. So there can be two places for
benchmarking.

First is the code that is responsible to take models and generate SQl. Second is the
code that uses `database/sql` to run the queries i.e measure how fast/efficient
are the generated queries.

The second part is too broad and vague, and might have different outcomes based
on the nature of the database. So the focus of ngorm is to make sure all the
cases are addressed, in a way that  the library generates the best possible
queries for the supported databases.

## Installation

	`go get -u github.com/ngorm/ngorm`

## Connecting to a database

NGORM uses a similar API as the one used by `database/sql` package to connect
to a database.

> connections to the databases requires importing of the respective driver

```go
package main

import (
	"log"

	// You must import the driver for the database you wish to connect to. In
	// this example I am using the ql and postgresql driver, this should work similar for the
	// other supported databases.

    // driver for postgresql database
	_ "github.com/ngorm/ngorm/postgres"
    // driver for ql database
	_ "github.com/ngorm/ngorm/ql"
	"github.com/ngorm/ngorm"
)

func main() {

	// The frist argument is the dialect or the name of the database driver that
	// you wish to to connect to, the second argument is connection information
	// please check the appropriate driver for more information on the arguments
	// that are passed to database/sql Open.
	db, err := ngorm.Open("ql-mem", "est.db")
	if err != nil {
		log.Fatal(err)
	}

	// Do something with db
}
```

>The returned `ngorm.DB` instance is safe. It is a good idea to have only one
>instance of this object throughout your application life cycle. Make it a global
>or pass it in context.
