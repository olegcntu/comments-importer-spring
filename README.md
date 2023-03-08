# Comments Importer

Spring Boot application completed as a test assignment. It imports comments from [dummyjson.com](https://dummyjson.com/comments), transforms them and stores them in a database.

## Features

- Fetches comments from the public API and maps them to DTOs
- Adds an `updatedAt` timestamp (`d-m-Y H:i:s`) and converts usernames to upper case
- Stores the data in the `users` table (MySQL)
- Renders the table on `/users` with Thymeleaf and Bootstrap
- The page is protected with Spring Security (admin registration and login)

## Tech stack

Java, Spring Boot, Spring Security, Spring Data JPA, Thymeleaf, Bootstrap, MySQL

## Getting started

Configure the MySQL connection in `application.properties`, then:

```bash
mvn spring-boot:run
```
