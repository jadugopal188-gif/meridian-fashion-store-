# Meridian Fashion Store — Demo Website

A responsive, premium black / cream / gold fashion storefront built with plain HTML, CSS and JavaScript. No build tools required.

## Run locally
Open `index.html` in a browser. Internet is needed for Google Fonts and the Unsplash product photography.

## Publish free with GitHub Pages
1. Create a GitHub repository, for example `meridian-fashion-store`.
2. Upload `index.html`, `styles.css`, `script.js` and this README to the repository root.
3. Open repository **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. The public URL will look like `https://YOUR-USERNAME.github.io/meridian-fashion-store/`.
6. Open the URL in a private/incognito window and test it on mobile.

## Features included
- Responsive homepage, shop section, category filters and price sorting
- Product detail modal and size selection
- Cart with quantity controls and localStorage persistence
- Demo checkout form and order confirmation message
- Contact form that prepares an email draft
- Demo newsletter form feedback
- Search, mobile navigation and toast messages

## Important production limitations
This is a **front-end demo**, not a production e-commerce backend:
- Checkout does not charge cards or process payments.
- Orders are not saved to a server or sent to a shop owner.
- Product inventory, accounts, tax, shipping calculations and order administration are not implemented.
- Newsletter subscriptions are not stored.
- The contact form opens an email draft; replace `hello@example.com` in `script.js` with the client's real contact email.
- Images are loaded from Unsplash and fonts from Google Fonts, so those assets need internet access.
- Before taking real orders, connect a backend/platform (for example Shopify or a secure custom backend) and a payment provider (for example Stripe or a suitable local provider). Never collect or store raw card details in front-end code.
- Product photos are external demo assets; replace them with client-owned or licensed images. “Meridian” is a demo brand name; check trademark availability before commercial use.

## Suggested client handover
Agree on scope, price, revisions, domain, hosting and maintenance in writing. Let the client own their domain and payment-provider accounts.
