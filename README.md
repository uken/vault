# Uken's SQL Test

### Build docker image
```
docker build . -t uken-sql-test
```
### Run docker image
```
docker run -d -p 5439:5439 uken-sql-test:latest
```
### Database Connection settings:
```
host: localhost
port: 5439
user: postgres
password: <empty>
database: postgres
```
