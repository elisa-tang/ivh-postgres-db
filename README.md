# ivh-postgres-db
InnoVet Health Postgres Database

## Build Database
```
docker build -t ivh-db .
```
## Run Database
```
docker run -d --name ivh-db -p 5432:5432 ivh-db
```