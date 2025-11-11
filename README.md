# 🛒 E-Commerce Website (MERN Stack)

A full-featured **E-commerce web application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.  
It provides a seamless shopping experience for users and a powerful admin dashboard for product and order management.

---

## 🚀 Features

### 👤 Authentication & Authorization
- Secure user registration and login
- Custom-built authentication system (JWT-based)
- Role-based access control (Admin, Customer)

### 🛍️ Shopping Features
- Product browsing with search and category filters
- Add to Cart and Checkout functionality
- Real-time UI updates on cart and product changes
- Order management and status tracking

### ⭐ Product Reviews
- Authenticated users can add, edit, and delete reviews
- Average rating displayed per product
- Review moderation in the admin panel

### 🧑‍💼 Admin Dashboard
- Add, update, or delete products
- Manage categories and customer orders
- Monitor customer activity and product inventory

### 💻 Responsive UI
- Built with **React.js** and **Tailwind CSS**
- Fully responsive across devices
- Clean and modern interface for customers and admins

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose ODM) |
| Authentication | JSON Web Tokens (JWT) |
| State Management | Context API / React Hooks |
| Deployment | Render / Vercel / Netlify (optional) |

---

## ⚙️ Installation & Setup

### Prerequisites
Make sure you have installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mern-ecommerce.git
   cd mern-ecommerce
````

2. **Install dependencies**

   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add:

   ```bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the development server**

   ```bash
   # Run backend
   npm run server

   # Run frontend
   cd client
   npm start
   ```

5. **Visit the app**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

---

---

## 🧠 Future Improvements

* Payment gateway integration (Stripe / PayPal)
* Wishlist and product recommendation system
* Advanced order analytics for admin
* Email notifications for order status updates

---
