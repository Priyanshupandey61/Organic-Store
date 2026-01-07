# 🌿 Organic Store – Full Stack Web Application

Organic Store is a full-stack e-commerce web application designed for selling organic products online. The project follows a clean separation of concerns where the frontend handles the user interface and the backend provides secure REST APIs for business logic, data handling, authentication, and payments.

---

## 📌 Project Overview

- **Frontend:** React (Vite-based Single Page Application)
- **Backend:** Node.js & Express (REST API)
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Payments:** Stripe
- **Architecture:** API-driven (Frontend ↔ Backend)

---

## ✨ Features

### 🛒 User Features
- Browse organic products
- View product details
- Add and remove products from cart
- Add and remove products from wishlist
- User authentication using JWT
- Place orders securely
- Online payment integration using Stripe

### ⚙️ Backend Features
- RESTful API architecture
- Product management APIs
- Cart and wishlist APIs
- Order management APIs
- Secure authentication and authorization
- Stripe payment gateway integration
- MongoDB database integration

---

## 🛠️ Tech Stack

### Frontend
- React 18
- Vite
- Material UI (MUI)
- Redux Toolkit
- React Router DOM
- Axios
- Yup (Form validation)
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- Stripe
- dotenv
- CORS

---

## 📁 Project Structure

```bash
organic-store/
├── frontend/
│   ├── index.html
│   ├── src/
│   ├── vite.config.js
│   └── package.json
│
├── backend/
│   ├── index.js
│   ├── data.js
│   ├── seed.js
│   ├── routes/
│   ├── models/
│   ├── .env
│   └── package.json
│
└── README.md
