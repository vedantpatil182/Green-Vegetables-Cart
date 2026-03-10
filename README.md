# Green(Vegetables)Cart - Full-Stack E-commerce Platform
#Live Demo 
https://green-cart-client-ten.vercel.app

GreenCart is a modern, feature-rich e-commerce platform built with the MERN stack (MongoDB, Express, React, Node.js). It features a sleek design, smooth animations, and robust functionality for both buyers and sellers.

## 🚀 Features

### 🛒 For Customers
- **User Authentication:** Secure login and signup functionality with JWT.
- **Product Discovery:** Seamlessly browse products across various categories.
- **Advanced Search:** Find specific products quickly using the search feature.
- **Shopping Cart:** Add, update, and remove items from the cart with real-time updates.
- **Address Management:** Save and manage multiple delivery addresses.
- **Seamless Checkout:** Integrated **Stripe Payment Gateway** for secure and fast transactions.
- **Order Tracking:** View order history and real-time status updates.

### 💼 For Sellers
- **Seller Dashboard:** Dedicated dashboard for managing business operations.
- **Inventory Management:** Easy-to-use interface to add, update, or delete products.
- **Image Uploads:** Powered by **Cloudinary** for efficient image management.
- **Order Overviews:** Track sales and manage incoming customer orders.

### 🛠️ Technical Highlights
- **Architecture:** Client-Server architecture for scalability.
- **Styling:** **Tailwind CSS** for a premium, responsive UI.
- **Security:** Protected routes using custom middleware and JWT authentication.
- **Database:** **MongoDB** with Mongoose for reliable data persistence.
- **Environment Management:** Secure configuration via `.env` files.

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS, Axios, React Router Dom
- **Backend:** Node.js, Express.js, JWT, Cookie-Parser
- **Database:** MongoDB (Mongoose)
- **Services:** Stripe (Payments), Cloudinary (Images)

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas account
- Stripe & Cloudinary accounts

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vedantpatil182/GreenCart.git
   cd GreenCart
   ```

2. **Backend Setup:**
   ```bash
   cd server
   npm install
   # Create a .env file and add your credentials (MONGODB_URI, JWT_SECRET, STRIPE_SECRET_KEY, etc.)
   npm run server
   ```

3. **Frontend Setup:**
   ```bash
   cd ../client
   npm install
   # Create a .env file and add VITE_BACKEND_URL
   npm run dev
   ```

---

## 🌐 Deployment

This project is optimized for deployment on **Vercel**. 
- Deploy the `server` folder as a Node.js API.
- Deploy the `client` folder as a React application.
- Remember to configure environment variables in your Vercel project settings.

---

## 📄 License
This project is licensed under the MIT License.
