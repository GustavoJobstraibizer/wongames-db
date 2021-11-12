## How to generate a dump

```bash
# run the following command to generate a dump
pg_dump -c --if-exists --exclude-table=strapi-administrator -h 127.0.0.1 -U strapi -d strapi -W > strapi.sql
```

### For insert data into the database

```bash
# run the following command to insert data into the database
postgres insert data into the Database:
psql -h 127.0.0.1 -U strapi -d strapi -W < strapi.sql
```