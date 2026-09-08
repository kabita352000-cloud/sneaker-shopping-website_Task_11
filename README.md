# Thala 7 Sneaker Store

Thala 7 Sneaker Store is a simple shoe shopping website made with **HTML, CSS, and basic JavaScript**.

Thala 7 Sneaker Store is a responsive, multi-page front-end web development project modeled after a modern sneaker e-commerce platform.

## Features

* 4 web pages: Home, Products, Cart, and Payment.
* Navigation bar to click and switch pages.
* Shoe image with a scrolling gallery underneath it.
* Quantity box that changes the total price when you type numbers.
* Remove button that deletes the shoe from the cart.
* Checkout form for typing email and fake credit card info.

## Project Files

Thala-7-Sneaker-Store/
│
├── index.html
├── products.html
├── cart.html
├── payment.html
├── style.css
│
└── images/
    └── shoe1.jpg

## Page Details

### Home Page (`index.html`)
The main entry page. It has a logo, links to other pages, a main shoe picture, a Shop Now button, and small boxes at the bottom showing user ratings and store information.

### Products Page (`products.html`)
Shows the shoe name, price (₹1,999), rating, and details. It has an input box to choose how many shoes you want, a row of scrollable pictures at the bottom, and an Add to Cart button.

### Cart Page (`cart.html`)
Has a two-column layout. The left side has a table showing the shoe, quantity box, price, and a red Remove button. The right side has a coupon box, a bill summary, and a Pay Now button.

### Payment Page (`payment.html`)
The checkout page. The left side has a form to type your email, pick a payment method (Cards/Crypto/Bank), and type card numbers. The right side shows your final bill.

## How the JavaScript Works

1. Changing Prices:** When you type a new number in the quantity box, the script multiplies ₹1,999 by that number to show the correct subtotal.
2. Saving Numbers (`localStorage`):** The pages use browser memory to pass numbers. If you pick 2 shoes on the product page, it saves that number and shows 2 shoes in your cart and payment pages automatically.
3. Delete Row:** Clicking the red Remove button deletes the shoe row from the page and sets all the bill amounts back to ₹0.

## How to Run the Website

1. Download this project folder to your computer.
2. Open the folder and check that your `images` folder has the `shoe1.jpg` file inside it.
3. Double-click `index.html` to open it in your regular web browser.
4. Click the links in the top menu to move between pages.

## Author
kabita kumari