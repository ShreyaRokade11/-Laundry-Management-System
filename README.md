# -Laundry-Management-System 
A full-stack Laundry Order Management System built using Spring Boot, MySQL, HTML, Bootstrap, and JavaScript. This project helps a laundry shop manage orders, track status, calculate bills, and view business reports.

This project helps a laundry shop manage orders, track status, calculate bills, and view dashboard reports.

---

## 🚀 Features

### 🧾 Order Management
- Create new laundry orders
- Update existing orders (Edit feature)
- Delete orders
- View all orders in table format

### 🔄 Order Status Tracking
- RECEIVED
- PROCESSING
- READY
- DELIVERED
- Update status dynamically

### 💰 Billing System
- Automatic total price calculation
- Print bill option (clean receipt format)

### 📊 Dashboard
- Total orders count
- Total revenue
- Processing orders count
- Ready orders count
- Delivered orders count

### 🔍 Search Feature
- Search by customer name
- Search by phone number

---

## 🛠️ Tech Stack

### Frontend:
- HTML5
- CSS3
- Bootstrap 5
- JavaScript (AJAX / Fetch API)

### Backend:
- Java
- Spring Boot
- Spring Data JPA
- REST API

### Database:
- MySQL

---

## 📂 Project Structure
Laundry-System
│
├── frontend
│ ├── index.html
│ ├── style.css
│ └── script.js
│
├── backend (Spring Boot)
│ ├── controller
│ ├── service
│ ├── repository
│ ├── model
│ └── application.properties
│
└── database
└── MySQL tables

1. 🔧 How to Run (VERY IMPORTANT)

Without this, your evaluator or recruiter can’t run your project.

👉 Add this section:

## ⚙️ How to Run Project

### 1. Clone Repository
git clone https://github.com/your-username/laundry-system.git

### 2. Backend Setup (Spring Boot)
- Open project in STS / IntelliJ
- Configure MySQL in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/laundry_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

- Run the Spring Boot application

### 3. Frontend
- Open index.html in browser

Backend runs on:
http://localhost:8080

## 🤖 AI Usage

### Tools Used:
- ChatGPT

### Where AI Helped:
- Designing REST APIs
- Fixing DELETE (405 error)
- Fixing EDIT (PUT not working)
- Dashboard logic
- Bill print UI

### Mistakes & Fixes:
- ❌ Wrong endpoint for DELETE → Fixed mapping
- ❌ PUT not working → Corrected controller
- ❌ Null values issue → Fixed in service layer
- ❌ Status not updating → Fixed API URL

  ## 👩‍💻 Developer
Shreya Rokade

## 🔮 Future Improvements

- Login Authentication
- Online Payment Integration
- SMS Notification
- Mobile Responsive UI
  
