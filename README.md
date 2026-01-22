# Byte Shop 🛍️

A modern, full-featured e-commerce application built with **React** and **Context API**. Byte Shop offers a seamless experience for both Buyers (Shopping List, Cart, Checkout) and Sellers (Inventory Management, Order Tracking).

![Byte Shop Banner](https://via.placeholder.com/1200x500?text=Byte+Shop+Screenshot) 
*(Note: Replace with actual screenshot)*

## ✨ Features

### 🛒 For Buyers
- **Product Browsing**: Clean, responsive grid layout for products.
- **Smart Search & Filters**: Search real-time and filter by Category (e.g., Smartphones, TVs).
- **Sort Options**: Sort products by Featured, Price Low-High, or Price High-Low.
- **Shopping Cart**: Add/Remove items, adjust quantities, and view live total calculation.
- **Checkout Simulation**: "Buy Now" flow with persistent order generation.

### 💼 For Sellers
- **Seller Dashboard**: A dedicated interface to manage the store.
- **Inventory Management**: simple form to **Add**, **Edit**, or **Delete** products.
- **Product Analytics**: View product details including Location and Price.
- **Order Tracking**: **NEW!** View "Incoming Orders" real-time table showing customer location, items, and status.

### 🔧 Tech Stack
- **Frontend**: React.js (Vite)
- **State Management**: React Context API
- **Styling**: Bootstrap 5 + Custom CSS
- **Persistence**: LocalStorage (Data survives page reloads)
- **Routing**: React Router DOM

## 🚀 Getting Started

Follow these steps to run the project locally.

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/byte-shop.git
   cd byte-shop
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run Development Server**
   ```bash
   npm run dev
   ```

4. **Open Browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal).

## 📂 Project Structure

```
src/
├── components/       # UI Components (Navbar, Cart, ProductCard, etc.)
├── ContextAPI/       # Global State (CartContext.jsx)
├── mocks/            # Dummy Data (Products.json)
├── App.jsx           # Main Router Setup
└── main.jsx          # Entry Point
```

## 🤝 Contributing

Contributions are welcome!
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
