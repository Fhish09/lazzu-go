# Lazzu Go — FoodGo Malta

A single-page food delivery web app for the Malta market.

**Live demo:** Open `index.html` in any modern browser (or serve it via GitHub Pages / any static host).

## Features

- **Restaurant browsing** – 6 realistic Malta restaurants (Pizza, Burgers, Maltese, Sushi, Healthy, Desserts)
- **Search & category filters**
- **Full menus** with prices in EUR (€)
- **Dish customisation** (extra toppings / remove ingredients) with live price updates
- **Cart** with subtotal, delivery fee (€1.80–€3.00), 5% service charge
- **Checkout** – Malta towns dropdown, ASAP or scheduled delivery, multiple payment methods
- **Order tracking** – animated status steps + courier moving on a simple map + countdown ETA
- **Role-based accounts**
  - Customer – order history, reorder
  - Restaurant Owner – accept/reject orders
  - Admin – overview stats + all orders
- **localStorage** persistence (cart, user, orders)
- Mobile-first responsive design with warm appetite-appealing colours

## Demo Accounts

| Role              | Email              | Password |
|-------------------|--------------------|----------|
| Customer          | customer@demo.com  | demo123  |
| Restaurant Owner  | owner@demo.com     | demo123  |
| Admin             | admin@demo.com     | demo123  |

Any other email + password `demo123` also works as a customer.

## Tech

- Single `index.html` file (inline CSS + JS)
- No backend / no build step required
- Pure vanilla HTML, CSS & JavaScript

## How to run

1. Clone the repo
2. Open `index.html` in your browser  
   *or*  
   `npx serve .` / any static server

Built for the Malta market 🇲🇹
