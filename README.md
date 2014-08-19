# Database Migration tools flywayを使ったサンプルコード

- http://flywaydb.org/documentation/maven/

## create database

```sql
mysql> create database example;
Query OK, 1 row affected (0.00 sec)
```

## flyway:init

```
$ mvn flyway:init -Dflyway.initVersion=0.0.0 -Dflyway.initDescription="Base version"
```

## flyway:migrate

```
$ mvn compile flyway:migrate
```
