# E-Commerce Web Application

## 📌 Overview
This is a full-stack **E-Commerce Web Application** that allows users to manage and purchase products seamlessly. The application provides functionalities such as adding, modifying, and deleting products, searching for products by name or category, adding them to the cart, and automatically updating stock levels upon purchase confirmation.

## 🛠️ Technologies Used
### Frontend:
- **HTML, CSS, JavaScript**
- **React.js**

### Backend:
- **Spring Boot**
- **MySQL (Database)**

### Backend Dependencies:
- **Spring Web** – Handles HTTP requests and RESTful API communication
- **Lombok** – Reduces boilerplate code (e.g., getters, setters, constructors)
- **Spring Data JPA** – Simplifies database interactions

## ⚙️ Features
### 🛒 Product Management
- Add, update, and delete products.
- Categorize products (e.g., Laptops, Computers, Accessories, etc.).
- Search products by name or category.

### 🛍️ Shopping Experience
- Add products to the cart.
- Confirm purchases and automatically update product quantity in stock.

### 📡 API Functionalities
- Perform **CRUD (Create, Read, Update, Delete)** operations on products.
- Fetch product details based on user search queries.
- Maintain seamless data interaction with MySQL using Spring Data JPA.

## 🚀 Setup and Installation
### Prerequisites:
- **Node.js & npm** (for frontend setup)
- **Java 17+** (for Spring Boot backend)
- **MySQL Database**
- **Maven** (for managing dependencies)

### 🔹 Clone the Repository
```sh
 git clone https://github.com/Manish27415/E-commerce.git
 cd E-commerce
```

### 🔹 Backend Setup (Spring Boot)
1. Navigate to the backend directory:
   ```sh
   cd backend
   ```
2. Configure the database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
   spring.datasource.username=root
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   ```
3. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```

### 🔹 Frontend Setup (React.js)
1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm start
   ```

## 🛡️ Security and Enhancements (Future Scope)
- User authentication and authorization (JWT-based authentication)
- Payment gateway integration
- Order history and user dashboard

## 📧 Contact
For queries or collaboration, reach out to **Manish27415** via GitHub.



