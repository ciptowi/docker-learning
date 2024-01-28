# Docker

## Docker pull Postgres image
```
docker pull postgres
```

## Docker run
“docker run --name -d <cont-name> -p 5432:5432 -e POSTGRES_PASSWORD=<password> postgres”
```
docker run --name mypostgresdb -e POSTGRES_PASSWORD=psql123 -p 5432:5432 -d postgres
```
