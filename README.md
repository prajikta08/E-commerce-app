# Luminary - E-Commerce App

A shopping web app built with React, Redux Toolkit, and JavaScript.

## Features

- Browse and filter products by category, price, rating, and search
- Add items to cart (cart is saved even after page refresh)
- 3-step checkout with shipping form and payment
- Payment gateway simulation (like Stripe)
- Order history page

## Tech Used

- React 18
- Redux Toolkit + redux-persist
- React Router DOM v6
- JavaScript & CSS

## How to Run

```bash
# 1. Clone the project
git clone https://github.com/your-username/luminary-ecommerce.git

# 2. Go into the folder
cd luminary-ecommerce

# 3. Install packages
npm install

# 4. Start the app
npm start
```

Then open `http://localhost:3000` in your browser.

## Test Payment Cards

| Card Number | Result |
|-------------|--------|
| 4242 4242 4242 4242 | Payment Success |
| 4000 0000 0000 0002 | Card Declined |

Use any future expiry date and any 3-digit CVC.

## Pages

| Route | Page |
|-------|------|
| `/` | Shop |
| `/cart` | Cart |
| `/checkout` | Checkout |
| `/orders` | Order History |
