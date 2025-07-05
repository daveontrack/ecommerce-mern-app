# 🛒 ECommerce MERN App

A modern, responsive, and full-featured **ECommerce Web Application** built with the **MERN Stack** – **MongoDB, Express, React, Node.js** – styled using **Tailwind CSS**, and managed through a powerful **Admin Dashboard**.

<p align="center">
  <img src="https://img.shields.io/github/license/daveontrack/ecommerce-mern-app" alt="License" />
  <img src="https://img.shields.io/github/last-commit/daveontrack/ecommerce-mern-app" alt="Last Commit" />
  <img src="https://img.shields.io/github/stars/daveontrack/ecommerce-mern-app" alt="Stars" />
</p>

---

## 🚀 Features at a Glance

### 👤 Customer Side
- 🔐 Secure User Auth (JWT)
- 🛍 Product Browsing with Filters
- 🛒 Cart & Seamless Checkout
- 📦 Order Placement & History
- 📱 Fully Responsive UI

### 🛠 Admin Dashboard
- 🔑 Role-Based Admin Access
- 📦 Product Management
- 📊 Sales & Order Analytics
- 👥 User Management
- 💬 Clean Tailwind-Based Interface

---

## 🧰 Tech Stack

| 🌐 Frontend             | ⚙️ Backend                | 🔧 Utilities & Tools     |
|------------------------|---------------------------|---------------------------|
| React + Vite           | Node.js + Express         | JWT Authentication        |
| Redux Toolkit          | MongoDB + Mongoose        | Cloudinary (optional)     |
| Tailwind CSS           | RESTful API               | Stripe / PayPal (optional) |
| React Router DOM       |                           |                           |

---

## 📸 Preview

| Home | Cart | Login | Admin Panel |
|------|------|-------|-------------|
| ![](https://via.placeholder.com/250x140?text=Home) | ![](https://via.placeholder.com/250x140?text=Cart) | ![](https://via.placeholder.com/250x140?text=Login) | ![](https://via.placeholder.com/250x140?text=Admin) |

---

## 🛠 Installation Guide

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/daveontrack/ecommerce-mern-app.git
cd ecommerce-mern-app
```

### 2️⃣ Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside `/server`:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm run dev
```

### 3️⃣ Frontend Setup

```bash
cd ../client
npm install
```

Start the frontend:

```bash
npm run dev
```

---

## 📁 Folder Structure

```
ecommerce-mern-app/
├── client/         # React frontend with Tailwind
│   ├── redux/      # Redux slices
│   ├── pages/      # Page components (User/Admin)
│   └── ...
├── server/         # Node/Express backend
│   ├── routes/     # REST API endpoints
│   ├── models/     # Mongoose schemas
│   └── ...
└── README.md
```

---

## ✨ Roadmap

- ✅ Stripe/PayPal Payment Integration  
- ✅ Product Ratings & Reviews  
- ✅ Email Notifications  
- 🚧 Inventory Management *(Coming Soon)*  
- 🚧 SEO Optimization + Sitemap *(Planned)*  
- 🚧 PWA Support *(Planned)*  

---

## 🔐 Demo Admin Credentials

```txt
Email: admin@example.com
Password: Admin@123
```

> ⚠️ Please **change credentials** in production. Use `.env` or secret managers for secure handling.

---

## 📜 License

Licensed under the [MIT License](LICENSE).  
You’re welcome to use, modify, and share freely.

---

## 🤝 Contributing

Contributions are welcome!  
Please fork the repo, create a branch, and submit a pull request.

> Let's build better commerce experiences — together.

---

## 👨‍💻 Developed By

**Dawit Mengesha Beriso**  
*Software Developer & UI/UX Enthusiast*

---

