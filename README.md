# secondproject
This project is Task 2 for the Spring Framework Apps assignment. The goal of this task is to create
a fully functional REST API using Spring Boot. The application supports CRUD operations,
exception handling, Swagger documentation, and an in-memory H2 database.
Technologies Used
• Java
• Spring Boot
• Spring Web (REST)
• Spring Data JPA
• H2 Database
• Swagger / OpenAPI
• Maven
How to Run the Application
1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run Project2Application.java
4. Application runs on port 8080
API Endpoints
POST /api/v1/products – create product
GET /api/v1/products/{id} – get product by id
GET /api/v1/products – get all products
PUT /api/v1/products/{id} – update product
DELETE /api/v1/products/{id} – delete product
H2 Database
URL: http://localhost:8080/console
JDBC URL: jdbc:h2:mem:testdb
User: sa
Password: (empty)
Swagger UI
URL: http://localhost:8080/swagger-ui/index.html
Application Architecture
Controller – handles HTTP requests
Service – business logic
Repository – database access using JPA
Mapper – maps request and response objects
<img width="2188" height="1333" alt="Screenshot 2025-12-22 172819" src="https://github.com/user-attachments/assets/8a6dc4be-cea8-4b54-986c-10612ebb3991" />

<img width="1098" height="557" alt="Screenshot 2026-01-13 220915" src="https://github.com/user-attachments/assets/de53c4fe-7e4b-4100-85a5-1c644fdf4159" />
<img width="1186" height="855" alt="Screenshot 2026-01-13 220829" src="https://github.com/user-attachments/assets/255ba996-f30f-4672-a335-141baae6e889" />
<img width="1192" height="772" alt="Screenshot 2026-01-13 220732" src="https://github.com/user-attachments/assets/2ad9a989-0d46-439e-a534-becee29aee90" />
<img width="1207" height="856" alt="Screenshot 2026-01-13 220643" src="https://github.com/user-attachments/assets/4afd577e-7a8d-4827-a061-d72d3227d0f6" />
<img width="1152" height="890" alt="Screenshot 2026-01-13 220628" src="https://github.com/user-attachments/assets/78eb0d9f-558f-4cdc-ba1b-3b7e7e050490" />
