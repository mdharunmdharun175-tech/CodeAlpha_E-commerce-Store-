# 🛒 e.com – Full Stack E-Commerce Web Application

A modern and fully functional **Full Stack E-Commerce Web Application** developed as part of the **CodeAlpha Internship Task**.
This project demonstrates real-world implementation of an online shopping platform with complete frontend, backend, and database integration.

---

## 📌 Internship Task (CodeAlpha)

**Task Title:** Basic E-Commerce Website

**Requirements:**

* Build a basic e-commerce website with product listings
* Frontend: HTML, CSS, JavaScript
* Backend: Django (Python) or Express.js (Node.js)
* Features:

  * 🛒 Shopping Cart
  * 📄 Product Details Page
  * 📦 Order Processing
  * 🔐 User Registration/Login
  * 🗄️ Database for products, users, and orders

🌐 Reference: [www.codealpha.tech](http://www.codealpha.tech)

---

## 🚀 Project Overview

This project is a **complete online shopping system** that allows users to:

* Register and login securely
* Browse products across multiple categories
* Add items to cart and wishlist
* Place orders with checkout system
* Manage personal profile and orders

It also includes an **Admin Panel** to manage products, users, and orders.

---

## ✨ Features

### 👤 User Features

* 🔐 User Authentication (Email / Phone login)
* 🛍️ Product browsing with categories
* 🔎 Live search functionality
* 📄 Product detail view
* 🛒 Add to cart system
* ❤️ Wishlist functionality
* 📦 Order placement & tracking
* 👤 Profile management

---

### 🛠️ Admin Features

* ➕ Add / Edit / Delete products
* 💰 Manage pricing
* 📦 Order management system
* 👥 User management

---

## 🏗️ Tech Stack

### 💻 Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### ⚙️ Backend

* Node.js
* Express.js

### 🗄️ Database

* SQLite (better-sqlite3)

---

## 📂 Project Structure

```
project/
│
├── frontend/
│   ├── index.html
│   ├── css/style.css
│   └── js/app.js
│
├── backend/
│   ├── server.js
│   ├── database/
│   └── uploads/
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ecom-project.git
cd ecom-project
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Run Backend Server

```bash
npm start
```

Server runs at:

```
http://localhost:3000
```

---

### 4️⃣ Run Frontend

#### Option 1: Live Server

* Open `index.html` in VS Code
* Right click → Open with Live Server

#### Option 2: Python Server

```bash
cd frontend
python -m http.server 5500
```

---

### 5️⃣ Connect Frontend to Backend

In `app.js`:

```js
const BASE_URL = 'http://localhost:3000';
```

---

## 🔐 Authentication & Security

* Session-based authentication
* Password hashing using bcrypt
* Secure API handling

---

## 📡 API Overview

| Method | Endpoint           | Description    |
| ------ | ------------------ | -------------- |
| POST   | /api/auth/register | Register user  |
| POST   | /api/auth/login    | Login user     |
| POST   | /api/auth/logout   | Logout user    |
| GET    | /api/products      | Fetch products |

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience in:

* Full Stack Web Development
* REST API Development
* Authentication Systems
* Database Integration
* UI/UX Design Principles

---

## 🔮 Future Enhancements

* 💳 Payment Gateway Integration
* 📱 Mobile App Version
* ⭐ Product Reviews & Ratings
* 📊 Analytics Dashboard

---

## 👨‍💻 Author

**Dharunkumar**
📧 Email: [mdharunmdharun175@gmail.com](mailto:mdharunmdharun175@gmail.com)
📞 Contact: 9342659272
- GitHub: [@dharun]([https://github.com/mdharunmdharun175-tech])
- Twitter: [@dharun46](https://x.com/Dharun_046)
- LinkedIn: [dharun-kumar](www.linkedin.com/in/dharun-kumar-m-691a04351)
- Portfolio: [dharunkumar.dev](https://yoursite.com)

---

## 🤝 Acknowledgment

This project was developed as part of the **CodeAlpha Internship Program**.

---

## 📜 License

This project is open-source and available under the MIT License.

---

⭐ If you like this project, give it a star!
