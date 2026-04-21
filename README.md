 🛒 ##Full Stack E-Commerce Product Catalog Application

A full-stack eCommerce product catalog application built using Spring Boot (Backend) and React (Frontend).
This project demonstrates REST API development, layered architecture implementation, and frontend-backend integration.


🚀 Tech Stack

Backend

- Java
- Spring Boot
- Spring Data JPA
- Hibernate (ORM)
- MySQL Database
- Maven

Frontend

- React.js
- JavaScript
- Bootstrap
- CSS
- Vite

---

🧱 Project Architecture

Backend follows Layered Architecture

Controller → Service → Repository → Database

Project Structure:

productcatalog
├── controller
├── service
├── repository
├── model
├── config (DataSeeder)
└── resources

Frontend:

ecom-catalog-react
├── components
├── assets
├── App.jsx
├── ProductList.jsx
└── CategoryFilter.jsx

---

✨ Features

✔ View product catalog
✔ Category-based filtering
✔ Search products by name
✔ Sort products by price
✔ REST API integration with frontend
✔ MySQL database integration
✔ Hibernate ORM mapping
✔ Sample data auto-loaded using DataSeeder
✔ Responsive UI using Bootstrap

---

🔗 Backend API Endpoints

GET /api/products

GET /api/categories

These APIs are consumed by the React frontend.

---

📸 Application Output

The application displays:

- Product name
- Description
- Category filtering
- Search functionality
- Price sorting
- Responsive product grid layout

---

⚙️ How to Run the Project

Run Backend (Spring Boot)

Open project in IntelliJ

Run:

ProductcatalogApplication.java

Backend runs on:

http://localhost:8080

---

Run Frontend (React)

Navigate to:

ecom-catalog-react

Run:

npm install
npm run dev

Frontend runs on:

http://localhost:5173

---

🗄 Database

Database used:

MySQL


---


👨‍💻 Author

Mohd Saif Nawaj
Java Backend Developer (Spring Boot)




