# 🛍️ Product Management System

A simple **Product Management System** built with **Next.js** where users can:
- Add new products
- View product details
- Manage products easily
- Use a secure login system before adding/viewing products

---

## 🚀 Live Demo
👉 [Live Site Link](https://product-manager-ass.vercel.app/)

## 💻 GitHub Repository
👉 [GitHub Repo Link](https://github.com/developerTamanna/product-management)

---

## 📌 Features
- 🔐 User Authentication (Login system)
- ➕ Add Product
- 📄 View Product Details
- 📋 Product List Page
- 🗂️ Organized Routes with Next.js App Router

---

## 🛠️ Tech Stack
- **Frontend**: Next.js, React, Tailwind CSS
- **Authentication**: JWT / NextAuth (যেটা ব্যবহার করেছো)
- **Database**: MongoDB / MySQL (যেটা ব্যবহার করেছো)
- **Hosting**: Vercel

---

## ⚙️ Setup & Installation

1. Clone the repository
   ```bash
   git clone https://github.com/developerTamanna/product-management
   cd product-management-system
Install dependencies

bash
Copy
Edit
npm install
Add your environment variables (.env.local)

bash
Copy
Edit
NEXT_PUBLIC_API_URL=your_api_url
DATABASE_URL=your_database_url
Run the development server

bash
Copy
Edit
npm run dev
Now open http://localhost:3000 in your browser.

📍 Route Summary
/ → Home Page

/login → User Login

/products → Product List

/products/[id] → Product Details

/products/add → Add New Product

