## 🏡 Airbnb Clone – Overview 🌍🚀
A fully functional Airbnb clone that enables users to list, search, and book rental properties worldwide. Designed for seamless user experience with secure authentication, dynamic listings, and an intuitive booking system.

## ✨ Features:
🔹 User Authentication – Sign up, log in, and manage profiles 👤🔐
🔹 Property Listings – Add, edit, and showcase rental spaces 🏠📸
🔹 Search & Filters – Find the perfect stay with advanced filters 🔍🏖️
🔹 Booking System – Securely book stays with real-time availability 📅✅
🔹 Reviews & Ratings – Leave feedback and rate stays ⭐📝
🔹 Responsive Design – Works seamlessly on all devices 📱💻

## 🚀 Tech Stack:

Frontend: HTML 🖥️, CSS 🎨, JavaScript ⚙️, EJS 📝
Backend: Node.js 🟩, Express.js 🚀
Database: MongoDB 💾, Mongoose 🐍
Auth: JWT 🔐
Other: Cloudinary ☁️, Mapbox 🗺️, Git 🧑‍💻, GitHub 🐙
Deployment: Render 🌐


## 🚀 Project Structure
```
airbnb-clone/
├── node_modules/
├── public/              # Static files (CSS, JS, Images)
│   ├── css/
│   ├── js/
│   └── images/
├── uploads/             # Uploaded images (if using local storage)
├── views/               # EJS templates
│   ├── partials/        # Navbar, footer, etc.
│   ├── listings/        # Listing-related pages
│   └── users/           # Login, signup pages
├── routes/              # Route handlers
│   ├── listings.js
│   ├── users.js
│   └── index.js
├── models/              # Mongoose models
│   ├── User.js
│   └── Listing.js
├── middleware/          # Custom middlewares
├── utils/               # Utility functions (e.g. cloudinary config)
├── .env                 # Environment variables
├── .gitignore
├── app.js               # Main application file
├── package.json
└── README.md
