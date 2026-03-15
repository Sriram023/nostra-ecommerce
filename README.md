# 🛍️ Nostra – E-Commerce Frontend (JavaScript Version)

## 📌 Overview

Nostra is a responsive e-commerce frontend built using **HTML, CSS, and JavaScript (ES6 Modules)**.  
It dynamically renders products using JavaScript and includes filtering functionality based on product tags.

This project demonstrates:

- Dynamic DOM manipulation
- ES6 module imports/exports
- Product filtering system
- Responsive layout design
- Clean UI structure

---

## 🚀 Features

- 🛒 Dynamic product rendering from `products.js`
- 🔍 Filter products by:
  - Occasion
  - Colors
  - Arrivals (New / Old)
- 📱 Responsive design
- 🎨 Modern UI with clean typography
- 🧩 Modular JavaScript structure

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6 Modules)

---

## 📂 Project Structure
Nostra/ │ ├── index.html ├── collections.html ├── style.css ├── collections.js ├── products.js ├── img/ │   └── products/ │       ├── f1.jpg │       ├── f2.jpg │       └── ... └── README.md
---

## 🧠 How It Works

Products are stored inside `products.js`:

```javascript
const products = [
  {
    id: 1,
    name: "Floral Summer Shirt",
    price: 220,
    tags: ["new", "blue", "summer"]
  }
]
