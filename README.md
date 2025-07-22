<img src="https://img.icons8.com/color/48/online-store.png" alt="Store Icon" style="height: 24px;"> <span>E-Commerce MERN Stack Application</span>



![MERN Stack](https://img.shields.io/badge/MERN-Stack-9cf)
![React](https://img.shields.io/badge/React-18-blue)
![Node.js](https://img.shields.io/badge/Node.js-16-green)
![MongoDB](https://img.shields.io/badge/MongoDB-5.0-brightgreen)
![License](https://img.shields.io/badge/License-MIT-success)

A full-featured E-COMMERCE platform built with the MERN stack (MongoDB, Express.js, React, Node.js) featuring modern UI, secure payments, and admin dashboard.

## ✨ Key Features

- **User Authentication**: JWT-based login/registration
- **Product Management**: CRUD operations for products
- **Shopping Cart**: Persistent cart functionality
- **Payment Gateway**: Stripe integration for secure payments
- **Admin Dashboard**: Manage products, users, and orders
- **Product Reviews**: Rating and review system
- **Responsive Design**: Mobile-friendly interface
- **Search & Filters**: Advanced product search functionality

## 🖥️ Tech Stack

**Frontend:**
- React.js 18
- Redux Toolkit (State management)
- React Router v6
- Axios (HTTP client)
- Tailwind CSS (Styling)
- React Icons

**Backend:**
- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM)
- JSON Web Tokens (Authentication)
- Bcrypt.js (Password hashing)
- Multer (File uploads)

**Payment:**
- Stripe API

## 🚀 Quick Start

### Prerequisites
- Node.js v16+
- MongoDB Atlas account or local MongoDB
- Stripe account (for payments)

### Installation

1. Clone the repository
```bash
git clone https://github.com/daveontrack/ecommerce-mern-app.git
cd ecommerce-mern-app
```

2. Install dependencies for both frontend and backend
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables
Create a `.env` file in the backend directory with:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
PORT=5000
```

4. Run the application
```bash
# From root directory
# Run server
cd server
npm run dev

# In another terminal, run frontend
cd ../client
npm start
```

The app should now be running on `http://localhost:3000`

## 📂 Project Structure

```
ecommerce-mern-app/
├── backend/
│   ├── config/         # Configuration files
│   ├── controllers/    # Route controllers
│   ├── models/         # MongoDB models
│   ├── routes/         # Express routes
│   ├── middleware/     # Custom middleware
│   ├── utils/          # Utility functions
│   └── server.js       # Express server
│
├── frontend/
│   ├── public/         # Static files
│   ├── src/
│   │   ├── assets/     # Images, styles
│   │   ├── components/ # React components
│   │   ├── features/   # Redux slices
│   │   ├── pages/      # Application pages
│   │   ├── services/   # API services
│   │   └── App.js      # Main App component
│   └── ...             # Other React config files
│
├── .gitignore
└── README.md
```


## 🛒 Features in Detail

### User Features
- ✅ User registration and login
- ✅ User profile management
- ✅ Product browsing with filters
- ✅ Product search functionality
- ✅ Product reviews and ratings
- ✅ Shopping cart system
- ✅ Checkout process with shipping
- ✅ Order history tracking

### Admin Features
- ✅ Product management (CRUD)
- ✅ User management
- ✅ Order management
- ✅ Sales analytics dashboard
- ✅ Product stock management

## 🧪 Testing

Run tests for both frontend and backend:

```bash
# Backend tests
cd server
npm test

# Frontend tests
cd ../server
npm test
```

## 🚀 Deployment

### Backend Deployment (Heroku)
```bash
# Login to Heroku CLI
heroku login

# Create new Heroku app
heroku create your-app-name

# Set environment variables
heroku config:set MONGO_URI=your_mongodb_uri JWT_SECRET=your_secret

# Deploy
git push heroku main
```

### Frontend Deployment (Netlify/Vercel)
1. Build the React app:
```bash
cd client
npm run build
```

2. Upload the `build` folder to your preferred hosting service

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

Project Maintainer - Email:(mailto:your.dawitberiso406@.com)  
Project Link - [https://github.com/daveontrack/ecommerce-mern-app](https://github.com/daveontrack/ecommerce-mern-app)

## 💖 Support

If you like this project, please??? give it a ⭐ on GitHub!

---

