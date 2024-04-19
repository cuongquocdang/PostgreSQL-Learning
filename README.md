# PostgreSQL Learning

## PostgreSQL

### Start Postgres Container

```sh
docker run --name postgres-learning -p 5432:5432 -e POSTGRES_PASSWORD=password -d postgres:16
```

### Start PgAdmin Container

```sh
docker run --name pgadmin-container -p 1080:80 -e PGADMIN_DEFAULT_EMAIL=admin@admin.com -e PGADMIN_DEFAULT_PASSWORD=password -d dpage/pgadmin4
```

## API
