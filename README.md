# Patel Clothing 🛍️

Stylish e-commerce storefront built with Create React App, SCSS modules, and Firebase for authentication & payments. Shop curated apparel, filter by category or price, manage your cart & favorites, and check out seamlessly—all in a responsive, modern interface. ✨

---

## 🌟 Features

* **Responsive Design**: mobile-first layout using SCSS Flexbox/Grid.
* **User Authentication**: signup/login via Firebase Auth (email & Google).
* **Product Catalog**: dynamic listings with search, category, and price filters.
* **Cart & Favorites**: add, update, or remove items; save favorites in real time.
* **Secure Payments**: integrated Firebase Functions for Stripe-based checkout.
* **State Management**: React Context API and custom hooks for clean, scalable code.

---

## 🛠️ Tech Stack

* React (Create React App) · JavaScript (ES6+)
* SCSS Modules · CSS Grid & Flexbox
* Firebase (Auth, Firestore, Functions)
* Stripe (via Firebase Functions)
* GitHub Pages for hosting

---

## 🚀 Getting Started

1. **Clone repository**

   ```bash
   git clone https://github.com/AdityaPatel2710/Patel-Clothing.git
   cd Patel-Clothing
   ```
2. **Install dependencies**

   ```bash
   npm install
   ```
3. **Configure Firebase**

   * Copy `.env.example` to `.env` and add your Firebase and Stripe keys.
   * Enable Auth, Firestore, and Functions in your Firebase console.
4. **Run locally**

   ```bash
   npm start
   ```
5. **Build for production**

   ```bash
   npm run build
   ```
6. **Deploy**

   * (Optional) `npm run deploy` to GitHub Pages
   * Deploy Firebase Functions with `firebase deploy --only functions`

---

## 🤝 Contributing

Contributions are welcome! Please fork the repo, create a feature branch, and submit a pull request.

---

© 2025 Aditya Patel – built with ❤️
