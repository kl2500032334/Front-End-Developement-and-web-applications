FoodExpress – how to run
1. Unzip the folder.
2. Double-click index.html (or open it with VS Code "Live Server").
3. Customers sign up on index.html. Admin logs in on the same page and is sent to admin.html.

Files
index.html    login + sign up
menu.html     menu, cart, my orders
payment.html  checkout
admin.html    dashboard, foods, orders, customers, notifications
css/style.css all styling
js/config.js  admin login, delivery fee, tax, default dishes
js/store.js   shared helpers   | auth.js, menu.js, payment.js, admin.js = page logic

Note: data lives in the browser (localStorage), so it is per device/browser.
For a real launch you need a backend + database and real payments (Razorpay etc.).
