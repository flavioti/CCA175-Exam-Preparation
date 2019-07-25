# Question

source: <http://cca175cloudera.training4exam.com/module-2>

You have been given MySQL DB with following details.

```text
user = retail_dba
password = cloudera
database = retail_db
table = retail_db.categories
jdbc URL = jdbc:mysql://quickstart:3306/retail_db
```

Please accomplish following activities.

- Connect MySQL DB and check the content of the tables.
- Copy "retaildb.categories" table to hdfs, without specifying directory name.
- Copy "retaildb.categories" table to hdfs, in a directory name "categories_target".
- Copy "retaildb.categories" table to hdfs, in a warehouse directory name "categories_warehouse".

## Answer

```bash
sqoop eval --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera"  -e "show tables;
```

```bash
sqoop eval --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera"  -e "select * from categories limit 1"
```

```bash
sqoop eval --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera"  -e "show tables;
```

```bash
sqoop eval --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera"  -e "show tables;"
```

```bash
sqoop import --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera" --table categories
```

```bash
sqoop import --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera" --table categories --target-dir categories_target
```

```bash
sqoop import --connect "jdbc:mysql://quickstart:3306/retail_db" --username "retail_dba" --password "cloudera" --table categories --warehouse-dir categories_warehouse
```
