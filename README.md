### DB with Docker

#### Mysql-5.7 Docker 
`docker run --name my-mysql-container -e MYSQL_ROOT_PASSWORD=1234 -p 3306:3306 -d mysql:5.7`

#### PostgreSQL Docker
`docker run --name my-postgres-container -e POSTGRES_USER=polak -e POSTGRES_PASSWORD=1234 -e POSTGRES_DB=test_db -p 5432:5432 -d postgres`
