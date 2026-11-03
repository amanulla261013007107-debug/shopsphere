# ShopSphere — Shopping Website Demo

ShopSphere is a responsive, front-end shopping website built with **HTML, CSS and vanilla JavaScript**. It is a self-contained demo, so it does not need a framework, package installation or a development server.

## Files

- `index.html` — the complete website, including its styling and JavaScript.
- `README.md` — this guide.

## Features

- Responsive layout for desktop, tablet and mobile screens
- Home page with featured products and category shortcuts
- Product catalogue with search and category filters
- Separate offers, cashback, enterprise and fashion sections
- Add-to-cart functionality
- Increase/decrease product quantities and remove items
- Cart subtotal and illustrative cashback estimate
- Demo bulk-purchase enquiry form with basic email validation

## How to run

1. Download or save `index.html` and `README.md` in the same folder.
2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox or Safari).
3. Browse the products and use **Add to cart** to test the cart.
4. No installation or internet connection is required for the demo.

## Customising products

Open `index.html` in a code editor and find the `products` array inside the `<script>` section. Each product has these fields:

- `id` — unique product number
- `name` — product name
- `category` — catalogue category
- `price` — current price in Indian rupees
- `oldPrice` — displayed previous price
- `emoji` — temporary product illustration
- `cashback` — illustrative cashback percentage

Edit the values to add, remove or update products. Give every product a unique `id`.

## Important limitations

This project is a **front-end demonstration**, not a production-ready online store.

- Product information and prices are sample data.
- Cashback percentages are illustrative and are not verified bank, card, wallet or merchant offers.
- The checkout button does not take payments or create orders.
- The enquiry form validates an email locally but does not send it.
- There is no database, user login, stock management, order history or admin dashboard.
- Cart contents are kept in browser memory and reset when the page is refreshed.

## Ideas for a production version

To turn this demo into a real shopping platform, connect it to:

1. A backend API and database for products, customers, stock and orders.
2. Secure authentication and role-based admin access.
3. A payment provider with a properly tested checkout flow.
4. Verified cashback and coupon integrations with clear terms.
5. Server-side validation, HTTPS, privacy controls and order notifications.

**Do not collect real customer or payment information through this demo.**
