# RedJr Builders and Construction Supply — Coded HCI Prototype

A responsive HTML, CSS, and JavaScript prototype based on the submitted RedJr interface. It uses the same light blue-gray background, white panels, blue primary buttons, green success accents, red alerts, and muted yellow status accents.

## Screens / views
1. Login
2. Dashboard
3. Products / POS
4. Orders
5. Inventory
6. Reports
7. Transaction checkout
8. Receipt / order confirmation
9. Transaction history

## Run locally
- Extract the ZIP file.
- Open `index.html` in a browser, or use VS Code with the Live Server extension.
- Demo login accepts any non-empty username and password.
- Add products to the cart, proceed to checkout, enter a customer name, and confirm the order to complete the main user flow.

## Deploy on Vercel
1. Extract this ZIP.
2. Create a new GitHub repository and upload `index.html`, `styles.css`, `app.js`, `vercel.json`, and `README.md` to the repository root.
3. Sign in to Vercel with GitHub and choose **Add New → Project**.
4. Import the repository.
5. For Framework Preset, choose **Other**. Leave Build Command and Output Directory empty if Vercel permits; this is a static site with no build step.
6. Click **Deploy**. Open the generated `.vercel.app` URL to test the prototype.

## Prototype notes
- Product, order, and transaction data are stored in the browser's `localStorage`; use the same browser to see saved changes.
- Login is for demonstration only and is not secure authentication.
- This is a front-end prototype, not a production inventory/POS system. It does not include a server database, real account management, or payment processing.
- Use fictional/demo customer details during the class demonstration.
