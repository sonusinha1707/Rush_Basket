<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# 🚀 Rush Basket Frontend

### 🖥️ Homepage
![Homepage Screenshot](https://github.com/sonusinha1707/Rush_Basket/blob/main/home.png)

### 🛒 Product Page
![Product Page Screenshot](https://github.com/sonusinha1707/Rush_Basket/blob/main/product.png)

This is the frontend repository for **Rush_Basket**, a modern e-commerce web application built with **React** and **Vite**. It offers a blazing-fast development experience, clean component-based architecture, and robust tooling to ensure code quality and maintainability.

---

## 🌟 Features

- ⚡ **Modern Development Workflow**: Powered by **Vite** for ultra-fast startup and Hot Module Replacement (HMR).
- 🧩 **Component-Based UI**: Built with **React**, enabling modularity, reusability, and efficient state management.
- ✅ **Code Quality**: Enforced with **ESLint**, including best practices and React-specific linting.
- 🗂️ **Efficient Asset Management**: Comes with a clean `index.html` and default favicon. SPA-ready.
- 🔄 **Backend Integration**: Structured to easily connect with a backend, with clear data models for orders and products.

---

## 📦 Getting Started

### ✅ Prerequisites

- **Node.js** (v18 or higher recommended)
- **npm** (comes with Node.js)

### 📥 Installation

Clone the repository and install dependencies:

```bash
git clone [repository-url]
cd frontend
npm install
```

### 🚀 Running the Development Server

Start the app with Hot Module Replacement:

```bash
npm run dev
```

Open your browser and go to [http://localhost:5173](http://localhost:5173).

### 📦 Building for Production

Create a production-ready optimized build:

```bash
npm run build
```

The compiled app will be output to the `dist` folder, ready for deployment.

---

## 🧹 Linting & Code Quality

This project uses **ESLint** to maintain clean and bug-free code.

Run the linter with:

```bash
npm run lint
```

### ESLint Configuration Includes:

- `@eslint/js`: ESLint’s recommended rule set.
- `eslint-plugin-react-hooks`: Ensures correct usage of React Hooks.
- `eslint-plugin-react-refresh`: Warns when components aren’t eligible for Fast Refresh.
- Custom rules: Ignores unused variables that start with `_` or capital letters.

---

## 📁 Project Structure

```
frontend/
├── public/              # Static assets
├── src/                 # Application source code
│   ├── components/      # React components
│   ├── pages/           # Route-level pages
│   ├── App.jsx          # Root React component
│   └── main.jsx         # React DOM entry point
├── index.html           # Main HTML file
├── vite.config.js       # Vite configuration
├── .eslintrc.js         # ESLint config
├── package.json         # Project metadata and scripts
└── .gitignore           # Files to ignore in Git
```

---

## 📊 Data Models

### 📦 Product Model

```js
{
  id: String,           // or productId / _id
  name: String,
  price: Number,
  imageUrl: String
}
```

### 🧾 Order Model

```js
{
  orderId: String,
  user: String,          // user ID
  customer: {
    name: String,
    email: String,
    phone: String,
    address: String
  },
  items: [
    {
      id: String,
      name: String,
      price: Number,
      quantity: Number
    }
  ],
  paymentMethod: String,   // e.g. "Cash on Delivery"
  shipping: Number,
  paymentStatus: String,   // 'Unpaid', 'Paid', etc.
  status: String           // 'Pending', 'Delivered', etc.
}
```

---

## 🧠 Credits

- Bootstrapped with [`create-vite`](https://vitejs.dev/guide/#scaffolding-your-first-vite-project)
- React template: Minimal setup for scalable projects
- ESLint config: Custom extension of React and JavaScript best practices

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---
>>>>>>> a83a641b1518633c2e85e1bb09d4b16d1d2303e5
