## Prerequisites
Ensure you have this installed before proceeding further
- Java 8
- Maven 3.3.9+
- Node 6.0 or above,  
- npm 4 or above,   
- Angular-cli

### Features of the Project
  * Token Based Security (using Spring security)
  * In Memory DB with H2
  * Using JPA and JDBC template to talk to relational database
  * How to request and respond for paginated data

* Frontend
  * Organizing Components, Services, Directives, Pages etc in an Angular App
  * How to chain RxJS Observables (by making sequntial AJAX request- its different that how you do with promises)
  * Techniques to Lazy load Data (Infinite Scroll)

### In Memory DB (H2)
I have included an in-memory database for the application. Database schema and sample data for the app is created everytime the app starts, and gets destroyed after the app stops, so the changes made to to the database are persistent only as long as the app is running
Creation of database schema and data are done using sql scripts that Springs runs automatically. To modify the database schema or the data you can modify.

### Maven Build : Navigate to the root folder where pom.xml is present
mvn clean install
java -jar ./build/libs/app-1.0.0.jar
java -jar ./target/app-1.0.0.jar
