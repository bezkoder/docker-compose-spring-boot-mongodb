# Docker Compose Spring Boot and MongoDB example

## Run the System
We can easily run the whole with only a single command:
```bash
docker compose up
```

Docker will pull the MongoDB and Spring Boot images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker compose down --rmi all
```

For more detail, please visit:
> [Docker Compose MongoDB and Spring Boot example](https://www.bezkoder.com/mongodb-docker-compose-spring-boot/)

Related Posts:
> [Spring Boot with MongoDB CRUD example](https://www.bezkoder.com/spring-boot-mongodb-crud/)

> [Spring Boot MongoDB Pagination & Filter example](https://www.bezkoder.com/spring-boot-mongodb-pagination/)

> [Spring Boot Reactive + MongoDB example](https://www.bezkoder.com/spring-boot-mongodb-reactive/)

> [Spring Boot + GraphQL + MongoDB example](https://www.bezkoder.com/spring-boot-graphql-mongodb-example-graphql-java/)

> [Spring Boot Validate Request Body](https://www.bezkoder.com/spring-boot-validate-request-body/)

> [Spring Boot and Swagger 3 example](https://www.bezkoder.com/spring-boot-swagger-3/)

> [Spring Boot Redis Cache example](https://www.bezkoder.com/spring-boot-redis-cache-example/)

> [Spring Boot File upload example](https://www.bezkoder.com/spring-boot-file-upload/)

> [Exception handling: @RestControllerAdvice example in Spring Boot](https://www.bezkoder.com/spring-boot-restcontrolleradvice/)

> [Spring Boot Rest Controller Unit Test with @WebMvcTest](https://www.bezkoder.com/spring-boot-webmvctest/)

Security:
> [Spring Boot: JWT Authentication & Authorization with MongoDB](https://www.bezkoder.com/spring-boot-jwt-auth-mongodb/)
