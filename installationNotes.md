# DOCKER
## Postgre Sql
**docker run --name postgres-0 -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:alpine** postgres image'ını çekip 5432 portunda çalıştırma.
**docker exec -it postgres-0 bash**  postgresql image'ını bashte çalıştırma .
**psql -U postgres** postgresql de user oluşturma.
