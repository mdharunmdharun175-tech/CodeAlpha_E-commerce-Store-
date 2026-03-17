# 🛒 e.com – Full Stack E-Commerce Web Application

A complete **Full Stack E-Commerce Web Application** built using modern web technologies to simulate a real-world online shopping experience.
This project was developed as part of the **CodeAlpha Internship Program**, fulfilling all required functionalities such as product listing, cart management, user authentication, and order processing.

---

## 📌 Project Description

The **e.com platform** is designed to provide a seamless and user-friendly online shopping experience.
It allows users to browse products, view detailed information, add items to cart, manage wishlist, and complete purchases through a structured checkout system.

The application also includes an **Admin Panel**, enabling administrators to efficiently manage products, users, and orders.

This project demonstrates:

* End-to-end full stack development
* Real-world application architecture
* Secure authentication and session handling
* API-driven frontend-backend communication
* Database integration for persistent storage

---

## 🎯 CodeAlpha Internship Task

### 🏢 Organization:

**CodeAlpha Internship Program**

### 📋 Task Objective:

Build a **Basic E-Commerce Website** with the following requirements:

* Product listing system
* Shopping cart functionality
* Product detail page
* Order processing system
* User registration and login
* Database for storing:

  * Users
  * Products
  * Orders

🌐 Reference: [www.codealpha.tech](http://www.codealpha.tech)

---

## 🚀 Key Functional Modules

### 🔐 1. Authentication Module

* User registration using email or phone
* Secure login system
* Password encryption using bcrypt
* Session-based authentication
* Logout functionality

---

### 🛍️ 2. Product Management Module

* Display products by categories
* Dynamic product listing
* Product detail modal with images and ratings
* Admin product CRUD operations

---

### 🛒 3. Cart System

* Add products to cart
* Update product quantity
* Remove items from cart
* Dynamic cart total calculation
* Slide-based cart UI

---

### ❤️ 4. Wishlist System

* Save favorite products
* Move items between wishlist and cart

---

### 📦 5. Order Processing System

* Checkout system
* Order placement
* Order history tracking
* Admin order management

---

### 👤 6. User Profile Module

* Update personal details
* Upload profile image
* Manage address and contact info
* Change password

---

### ⚙️ 7. Admin Panel

* Add / edit / delete products
* Manage users
* View and manage orders
* Control pricing and inventory

---

## 🏗️ System Architecture

This project follows a **client-server architecture**:

### 🔹 Frontend (Client)

* Handles UI rendering and user interaction
* Sends API requests to backend
* Built using Vanilla JavaScript (SPA approach)

### 🔹 Backend (Server)

* Handles business logic
* Provides REST APIs
* Manages authentication and sessions

### 🔹 Database

* SQLite database used for storing:

  * Users
  * Products
  * Orders

---

## 🏗️ Tech Stack

### 💻 Frontend Technologies

* HTML5
* CSS3 (Responsive UI Design)
* JavaScript (Vanilla JS)

### ⚙️ Backend Technologies

* Node.js
* Express.js

### 🗄️ Database

* SQLite (better-sqlite3)

### 🔐 Security

* bcrypt (Password hashing)
* express-session (Session management)

---

## 📂 Project Structure

```id="str002"
project-root/
│
├── frontend/
│   ├── index.html        # Main application UI
│   ├── css/style.css     # Styling & layout
│   └── js/app.js         # Client-side logic
│
├── backend/
│   ├── server.js         # API & server logic
│   ├── db/               # Database setup & queries
│   └── uploads/          # User uploaded files
│
├── package.json          # Dependencies
└── README.md
```

---

## ⚙️ Installation Guide

### 🔹 Step 1: Clone Repository

```bash id="cmd5"
git clone https://github.com/your-username/ecom-project.git
cd ecom-project
```

---

### 🔹 Step 2: Install Dependencies

```bash id="cmd6"
npm install
```

---

### 🔹 Step 3: Start Backend Server

```bash id="cmd7"
npm start
```

Server runs at:

```id="url2"
http://localhost:3000
```

---

### 🔹 Step 4: Run Frontend

#### Option 1: Live Server

* Open `index.html`
* Right click → Open with Live Server

#### Option 2: Python Server

```bash id="cmd8"
cd frontend
python -m http.server 5500
```

---

### 🔹 Step 5: API Connection

Update backend URL in:

```js id="code2"
const BASE_URL = 'http://localhost:3000';
```

---

## 🔐 Security Implementation

* Passwords stored in encrypted format
* Session-based login system
* Protected routes for admin access
* Input validation and error handling

---

## 📡 API Design

RESTful APIs are used for communication:

| Category | Endpoint           | Description   |
| -------- | ------------------ | ------------- |
| Auth     | /api/auth/register | Register user |
| Auth     | /api/auth/login    | Login user    |
| Auth     | /api/auth/logout   | Logout        |
| Products | /api/products      | Get products  |
| Orders   | /api/orders        | Create order  |

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Full Stack Web Development
* REST API Development
* Authentication & Authorization
* Database Design & Queries
* UI/UX Design Principles
* Debugging and Error Handling

---

## 🔮 Future Enhancements

* 💳 Online Payment Integration (Razorpay/Stripe)
* ⭐ Product Review & Rating System
* 📱 Mobile App Version
* 📊 Admin Analytics Dashboard
* 🚀 Performance Optimization

---

## 👨‍💻 Author

**Dharunkumar**

📧 Email: [mdharunmdharun175@gmail.com](mailto:mdharunmdharun175@gmail.com)
📞 Contact: 9342659272

🔗 LinkedIn: https://linkedin.com/in/your-id
🐙 GitHub: https://github.com/your-id
🐦 Twitter: https://twitter.com/your-id

---

## 🤝 Acknowledgment

This project was developed as part of the **CodeAlpha Internship Program**, focusing on real-world full stack development skills.

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you like this project, please give it a star!
