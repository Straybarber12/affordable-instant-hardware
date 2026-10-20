# Affordable & Instant Hardware — VS Code starter project

A responsive front-end prototype for **Affordable & Instant Hardware**, an online hardware supply and sourcing service for Zimbabwe. Brand positioning: **Affordable supplies. Fast sourcing.** The site helps customers browse demo products, build a shopping list, and prepare a supplier quotation request, with a floating Tendai AI assistant interface.

## Run it

1. Download and extract the project ZIP.
2. Open the extracted `affordable-instant-hardware` folder in Visual Studio Code.
3. Open `index.html` in a browser. Recommended: install the **Live Server** extension in VS Code, right-click `index.html`, and choose **Open with Live Server**.

No build step or package installation is required for this prototype.

## Included features

- Responsive homepage and hardware product categories
- Search and sorting for demo products
- Add items to a shopping list and change quantities
- Illustrative order total
- Quotation form that prepares a message for the customer to review
- Floating Tendai AI panel with demo responses and suggested prompts
- Mobile navigation and responsive layout

## Important before launch

- Product catalogue, prices and stock are examples only, not real supplier data or quotations.
- Tendai currently uses demo response rules. It is not connected to a live AI model.
- The quote form does not submit to a server or process payments; it prepares a message for review.
- Product photos and Google Fonts load from external URLs and may require internet access.
- No customer information is saved to a database.
- Confirm actual supplier availability, selling prices, delivery charges, business contact details, and any applicable legal requirements before accepting real orders.
- Never place a private AI API key in `app.js` or any browser-side code. Use a secure server-side endpoint when adding live AI.

## Suggested next steps

1. Replace sample products with verified products, prices, units and last-updated dates.
2. Add a database and secure admin dashboard for products, supplier quotes and customer orders.
3. Connect Tendai to an AI API through a secure server-side endpoint.
4. Add verified supplier quote comparison and delivery-cost calculations.
5. Add real business contact details and a secure payment option only when ready.

## Project files

- `index.html` — page structure and forms
- `styles.css` — responsive design
- `app.js` — demo product catalogue, search, shopping list, quote form and demo assistant
