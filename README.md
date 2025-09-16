# Employee Payroll Management System (Spring Boot)

A web-based payroll management system built with Spring Boot, Thymeleaf, Spring Data JPA, and H2/MySQL.

## Features
- Add / View / Edit / Delete employees
- Automatic salary calculation (HRA, DA, Deductions)
- Payslip generation (Thymeleaf)
- H2 in-memory DB for quick demo, switch to MySQL for production.

## Tech Stack
- Java 17, Spring Boot, Spring Data JPA, Thymeleaf
- H2 (demo) / MySQL (production)
- Maven

## Quick Run (H2)
1. `mvn clean spring-boot:run`
2. Open `http://localhost:8080/`

## MySQL Setup
1. Create DB: `CREATE DATABASE payrollDB;`
2. Update `application.properties` with MySQL creds.
3. `mvn clean spring-boot:run`

## Author
Prerana Patil — https://github.com/perupatil
