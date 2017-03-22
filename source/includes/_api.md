# API

ngorm api borrows heavily from gorm. 

## `DB.AddForeignKey`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```


## `DB.AddIndex`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.AddUniqueIndex`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```
## `DB.Assign`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Association`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Attrs`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Automigrate`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.CommonDB`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Count`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.CreateTable`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Delete`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Dialect`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.DropColumn`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.DropTable`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.DropTableIfExests`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Find`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.First`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.FirstOrCreate`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.FirstOrInit`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Group`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.HasTable`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Having`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Set`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Joins`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Last`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Limit`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Model`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

##  `DB.ModifyColumn`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Not`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Offset`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Omit`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Or`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Order`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```


## `DB.Pluck`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Preload`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

##`DB.Related`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.RemoveIndex`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Save`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Select`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.SingulatTable`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Table`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Update`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.UpdateColumn`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.UpdateColumns`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Updates`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```

## `DB.Where`

```go
 db.Model(User{}).AddForeignKeySQL("city_id", "cities(id)", "RESTRICT", "RESTRICT")
```

> Generates 

```sql--ql
-- ql has no support for foreign keys
```

```sql--postgresql
ALTER TABLE "users" ADD CONSTRAINT "users_city_id_cities_id_foreign" FOREIGN KEY ("city_id") REFERENCES cities(id) ON DELETE RESTRICT ON UPDATE RESTRICT;
```
