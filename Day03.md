**Prerequisite**: Ensure you tag your master branch as _day02_ before working on Day 3 tasks.

# Day 3
1. Configure your project to use an embedded database (HSQL) to store Customer data.  (update dependencies in the build file, create schema.sql). **Note:** All fields are mandatory. 
2. Hard-code 2-3 sample records using data.sql.
3. Implement the domain and repository layers so they use JPA to access the embedded database.
4. Implement the service layer (the interface and implementation) to use all repository layer operations.
5. Implement the Customer data API with full CRUD capabilities using Spring Boot. Ensure you return the appropriate status code and also data where applicable. 
6. Use the Gradle build process to build and run Customer data API
7. Use Postman to test service endpoints and verify CRUD capabilities of the service
8. Test the service endpoints using the front-end react client
9. Repeat task 1 through 8 to implement and test Event data API
10. Repeat task 1 through 8 to implement and test Registrations data API
11. Demonstrate the service and build process
12. Commit the completed API code and Gradle files to your local repository and also merge changes into the GitHub remote repository.
