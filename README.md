# Paradise Nursery - Plant Shopping Application

A React-based e-commerce web application for purchasing plants online, built as part of the IBM Developer Skills Network course.

## Project Overview

Paradise Nursery is an online plant shop that allows users to browse a wide variety of plants, add them to a shopping cart, and manage their purchases. The application features a clean, intuitive interface with a nature-inspired design.

## Features

- **Landing Page** - Welcome page with company branding and "Get Started" button
- **Product Listing** - Browse plants organized by category with images, descriptions, and prices
- **Shopping Cart** - Add, remove, and update quantities of plants in the cart
- **Real-time Cart Updates** - Cart total and item count update dynamically
- **Responsive Design** - Background image and styled UI components

## Plant Categories

- Air Purifying Plants
- Aromatic Fragrant Plants
- Insect Repellent Plants
- Medicinal Plants
- Low Maintenance Plants

## Tech Stack

- React 18
- Redux Toolkit (State Management)
- Vite (Build Tool)
- CSS3

## Project Structure
e-plantShopping/
├── src/
│   ├── App.jsx          # Landing page with Get Started button
│   ├── App.css          # Global styles and background image
│   ├── AboutUs.jsx      # Company information page
│   ├── ProductList.jsx  # Plant catalog with Add to Cart functionality
│   ├── CartItem.jsx     # Shopping cart with quantity management
│   ├── CartSlice.jsx    # Redux slice for cart state management
│   └── store.js         # Redux store configuration
├── public/
└── package.json

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm

### Installation

1. Clone the repository:
git clone https://github.com/Jstudio26/e-plantShopping.git

2. Navigate to the project directory:
cd e-plantShopping

3. Install dependencies:
npm install

4. Start the development server:
npm run dev

5. Open your browser and visit `http://localhost:5173`

## Usage

1. Open the app to see the Paradise Nursery landing page
2. Click **"Get Started"** to browse the plant catalog
3. Click **"Add to Cart"** on any plant to add it to your cart
4. Click the cart icon in the navbar to view your cart
5. Use **+** / **-** buttons to adjust quantities
6. Click **Delete** to remove an item from the cart
7. Click **Continue Shopping** to return to the catalog

## License

This project is part of the IBM Full Stack Software Developer Professional Certificate program.
