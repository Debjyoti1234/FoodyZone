## FoodyZone — Complete Frontend Project

A multi-page online food ordering system built with HTML5, CSS3 and Vanilla JavaScript.

## Features
- Home page and restaurant discovery
- Individual restaurant detail/menu pages
- Search restaurants and browse menu items
- Add-to-cart, quantity controls and persistent cart
- Coupon codes: `WELCOME100` (₹100 off on ₹399+) and `FOODY10` (10% off, capped at ₹150, on ₹299+)
- Bill breakdown: item total, delivery fee, platform fee, estimated GST and discount
- Delivery location and saved addresses
- Checkout form and demo order placement
- Order history, simulated tracking stages and reorder
- Wishlist/favourites
- Customer reviews (local demo data)
- Profile details stored locally
- Admin demo dashboard with sample order-status management and adding sample menu items
- Responsive layout

## Run
1. Extract the ZIP.
2. Open the folder in VS Code.
3. Run `index.html` with Live Server. No build tools are required.

## Demo limitations / security
This is a frontend-only academic project. It does not have a backend, secure login, server-side admin permissions, live GPS, real restaurant inventory, real delivery tracking, or payment processing. Data is stored in browser localStorage and is specific to the browser/device. The admin page is for demonstration only and must not be used with real customer data. Fees and tax are illustrative sample calculations, not actual merchant charges.


## Suggested group division (5 members)
1. Home, shared navigation, responsive CSS.
2. Restaurant discovery, restaurant details and menu.
3. Cart, coupon engine and bill calculation.
4. Checkout, profile, addresses, wishlist and orders.
5. Admin demo, reviews, QA, documentation and GitHub release.

All members should understand the overall app flow and be able to explain the localStorage data model during viva.

