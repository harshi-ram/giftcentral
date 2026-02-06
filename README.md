# MERN GiftShop – User‑Driven Gift Marketplace

A full‑stack MERN e‑commerce application where users can browse gifts, manage carts, place orders, and even act as sellers by listing their own products. Built with scalability, clean architecture, and real‑world e‑commerce flows in mind.

Extended from https://github.com/ajaybor0/MERN-eCommerce

---

## Features

* Seamless shopping cart functionality for users to add, remove, and manage products.
* Users can leave reviews and provide ratings for products.
* Navigate through products efficiently with pagination.
* Easily search for products based on keywords.
* User profiles with editable personal information
* Seller accounts allowing users to list and manage their own products
* Custom gift request system for buyer-to-seller interactions
* Real-time buyer–seller chat
* Mailbox and real-time notifications system

---

## Tech Stack

### Frontend

* React.js
* CSS

### Backend

* Node.js
* Express.js
* MongoDB 
---

## Environment Variables

Create a `.env` file in the backend directory:

```
NODE_ENV=development
PORT=5000
JWT_SECRET=
MONGO_URI=
RAZORPAY_KEY_ID=ADD_YOUT_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
```

---

##  Getting Started

### Clone the repository

```
git clone https://github.com/harshi-ram/giftcentral-marketplace.git
cd giftcentral-marketplace
```

### Install dependencies

Backend:

```
cd backend
npm install
```

Frontend:

```
cd frontend
npm install
```

### Run the application

Backend:

```
npm run dev
```

Frontend:

```
npm start
```

---
