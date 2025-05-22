A simple yet functional e-commerce platform built as a mini project for the Web Technology & Internet (INSY-413) course. The application is developed using Spring Boot for the backend and Thymeleaf for the frontend.

📌 Features
👤 Customer Capabilities
Browse products and view detailed information.

Add/remove products to/from the shopping cart.

View cart contents and proceed to checkout.

Register and log in to manage personal orders.

🛠️ Admin Capabilities
Add, update, or remove products.

View and manage customer orders and update their status.

🧱 Tech Stack
Backend: Spring Boot, Spring Data JPA, Spring Security

Frontend: Spring MVC, Thymeleaf

Database: MySQL/PostgreSQL

Styling: Bootstrap/Material UI

Deployment: Heroku/AWS/Azure

🚀 Getting Started
Prerequisites
Java 17+

Maven or Gradle

MySQL/PostgreSQL

Git

Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/ecommerce-spring-thymeleaf.git
cd ecommerce-spring-thymeleaf
Setup Instructions
Configure the database in application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce
spring.datasource.username=root
spring.datasource.password=yourpassword
Run the Application:

bash
Copy
Edit
./mvnw spring-boot:run
Access the app at: http://localhost:8080

🔐 User Roles
USER: Can register, login, browse products, manage cart, and place orders.

ADMIN: Can manage products and view/update orders.

📦 Key Modules
Backend (Spring Boot)
REST APIs for products, cart, orders

Role-based authentication (Spring Security)

JPA entities: User, Product, Order, OrderItem

Frontend (Thymeleaf)
Product listing and detail pages

Login, signup, and authentication flow

Cart and checkout UI

Admin dashboard for product and order management

⚠️ Error Handling
Server and client-side validation

User-friendly error messages

Custom exception handling with global error controller

☁️ Deployment
The app can be deployed on cloud platforms such as:

Heroku

AWS EC2

Azure Web Apps

📂 Documentation
Project source code and documentation are available at:
GitHub Repository

📝 License
This project is for educational purposes and distributed under the MIT License.

