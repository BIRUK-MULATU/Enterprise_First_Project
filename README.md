ShopWave Starter — SE 4801 Assignment 1

  **Student Information**
Field                 Details
Name                Biruk Mulatu
Student Number      ATE/9686/14
Course              SE 4801 — Enterprise Application Development
University          CTBE
Department          Software Engineering

**What is this project**
ShopWave Starter is a RESTful API built with Java 21 and Spring Boot 3.x for managing a simple product catalogue. It was developed as part of Assignment 1 for SE 4801 — Enterprise Application Development.
The project covers the full Spring Boot application layer stack from JPA entities and repositories, all the way up to REST controllers and global exception handling. 
It uses an H2 in-memory database so there is no database installation required to run it.

**How to build**
make sure you have java 21 and maven installed first
       mvn clean package -DskipTests

**How to Run**
Using IntelliJ IDEA:Open
ShopWaveApplication.java and click the green play button next to the main method.
Once started, the app runs on: http://localhost:8080

**How to Run Tests**
mvn test
You should see output like: Tests run: 8, Failures: 0, Errors: 0, Skipped: 0
BUILD SUCCESS
