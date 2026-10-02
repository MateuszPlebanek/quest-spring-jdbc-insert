# Spring JDBC Insert Challenge

Project completed as part of a Spring Boot and JDBC exercise.

## Objective

The goal of this project is to create a school from an HTML form and insert it into a MySQL database using JDBC.

## Technologies Used

- Java
- Spring Boot
- JDBC
- MySQL
- Thymeleaf
- HTML
- CSS
- Maven

## Features

- Display a form to create a school
- Send form data with a POST request
- Insert a new school into the database
- Use `PreparedStatement`
- Use `executeUpdate()`
- Retrieve the generated school ID
- Display the created school after insertion

## Route

Create a school:

```text
http://localhost:8080/school/create
