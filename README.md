spring boot, spring batch, and postgres
===

This shows an integration with spring boot 2.x, spring web, spring batch, and postgres to kick off a simple workflow.

It is based off of [spring examples](https://github.com/spring-guides/gs-batch-processing)

```
# start postgres
docker-compose up

# start spring boot application (or use your editor)
./gradlew bootRun

curl -X post http://localhost:8080/jobs/start
```

Cloned from: 
https://github.com/NickTomlin/spring-batch-postgres-example/tree/master/src/main/java/com/example/pgbatch
