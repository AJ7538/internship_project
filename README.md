# E-Commerce Frontend (React)

A fully functional **frontend e-commerce application built with React.js** during my internship.
The project focuses on creating a responsive and interactive shopping interface that simulates a real-world online store.

---

## Overview

This project implements the frontend of an online shopping platform using **React and modern JavaScript practices**.
Users can browse products, view product details, add items to a cart, and manage their shopping session through a dynamic interface.

The application is designed with a **component-based architecture**, ensuring scalability and maintainability.

---

## Features

* Product catalog browsing
* Product detail pages
* Add to cart functionality
* Cart management (add, remove, update quantity)
* Responsive UI for mobile and desktop
* Dynamic rendering using React components
* State management for cart operations
* Modular and reusable component structure

---

## Tech Stack

Frontend Framework

* React.js

Languages

* JavaScript (ES6+)
* HTML5
* CSS3

Tools

* Git
* GitHub
* Node.js
* npm

---

## Project Structure

```
vilora-react/
│
├── public/
│   ├── index.html              # HTML entry point
│   └── vilora_logo.png         # Your logo (add manually)
│
├── src/
│   ├── App.jsx                 # Root — page routing + all providers
│   ├── index.js                # React entry point
│   ├── styles.js               # All global CSS injected here
│   │
│   ├── components/
│   │   ├── AboutSection.jsx    # About section with numbered features
│   │   ├── CartDrawer.jsx      # Slide-in cart drawer
│   │   ├── CheckoutModal.jsx   # 3-step checkout (address → payment → confirm)
│   │   ├── ContactSection.jsx  # Contact form + info
│   │   ├── Cursor.jsx          # Custom gold cursor + ring
│   │   ├── Footer.jsx          # Dark 4-col footer with newsletter
│   │   ├── Hero.jsx            # Full-height hero with stats
│   │   ├── Loader.jsx          # Page load animation
│   │   ├── Navbar.jsx          # Sticky dark navbar, scroll-tracked links
│   │   ├── ProductCard.jsx     # Individual product card with wishlist
│   │   ├── ProductModal.jsx    # Product detail modal
│   │   ├── ProductsSection.jsx # Category filter + search + product grid
│   │   └── Sections.jsx        # HowItWorks, Stats, Testimonials, CTA
│   │
│   ├── context/
│   │   ├── AuthContext.jsx     # Login/logout + role (user/admin)
│   │   ├── CartContext.jsx     # Cart state with useReducer
│   │   ├── OrderContext.jsx    # Orders + users mock data
│   │   ├── ToastContext.jsx    # Toast notification stack
│   │   └── WishlistContext.jsx # Wishlist toggle state
│   │
│   ├── data/
│   │   └── products.js         # 12 products, categories, testimonials
│   │
│   ├── hooks/
│   │   └── useReveal.js        # IntersectionObserver scroll reveal hook
│   │
│   └── pages/
│       ├── AdminDashboard.jsx  # Admin — stats, orders, products, users
│       ├── LoginPage.jsx       # Login / signup with role-based redirect
│       ├── TrackOrder.jsx      # Live order timeline tracker
│       └── UserDashboard.jsx   # User — orders, wishlist, profile, loyalty
│
├── package.json                # Dependencies + scripts
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/YOURUSERNAME/repository-name.git
```

2. Navigate into the project folder

```
cd repository-name
```

3. Install dependencies

```
npm install
```

4. Start the development server

```
npm start
```

The app will run on:

```
http://localhost:3000
```

## Learning Outcomes

Through this project I gained experience in:

* Building scalable UIs using **React components**
* Managing UI state for shopping cart functionality
* Structuring large frontend projects
* Creating responsive layouts for e-commerce applications

---

## Internship Context

This project was developed during my internship at **DeepQuantica**.

The repository is shared **only for portfolio and demonstration purposes** with permission from the company.
All intellectual property belongs to the company.

---

## Author

Ayaz
Computer Science Student

GitHub: https://github.com/AJ7538
