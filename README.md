# Online Grocery Template

A responsive static storefront prototype for a neighborhood sari-sari shop. Fresh Nook lets customers browse everyday groceries, review product details, manage a basket, and step through a checkout experience.

## Features

- Grocery storefront homepage with delivery messaging and featured deals
- Product categories and filtering UI
- Product quick-view page with quantity controls
- Basket summary and order totals
- Checkout flow with delivery address and payment selection
- Sign-in page
- Account area with profile, payment, address, and order-history sections
- Responsive layouts for mobile and desktop screens
- Custom visual styling built around the Fresh Nook brand

## Pages

| Page       | File                                               | Purpose                                                |
| ---------- | -------------------------------------------------- | ------------------------------------------------------ |
| Home       | [`index.html`](index.html)                         | Storefront landing page, search, categories, and deals |
| Category   | [`category.html`](category.html)                   | Browse produce and apply product filters               |
| Quick view | [`product-quickview.html`](product-quickview.html) | Inspect a product and adjust quantity                  |
| Basket     | [`cart.html`](cart.html)                           | Review selected items and totals                       |
| Checkout   | [`checkout.html`](checkout.html)                   | Select delivery details and payment method             |
| Sign in    | [`login.html`](login.html)                         | Customer sign-in screen                                |
| Account    | [`account.html`](account.html)                     | Manage account details and order-related information   |

## Tech Stack

- Semantic HTML
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Bootstrap Icons](https://icons.getbootstrap.com/) via CDN
- [Google Fonts](https://fonts.google.com/) using Anton and Work Sans
- Custom CSS in [`assets/css/style.css`](assets/css/style.css)
- WebP product and hero imagery in [`assets/images/`](assets/images/)

## Getting Started

No installation or build step is required.

### Option 1: Open directly

Open [`index.html`](index.html) in a modern browser.

### Option 2: Run a local server

Serving the files locally gives the most reliable browser behavior. From the project root, run one of the following commands:

```bash
# Python 3
python -m http.server 8000
```

Then visit <http://localhost:8000>.

Alternatively, use any static file server or a VS Code live-server extension.

## Project Structure

```text
.
├── account.html
├── cart.html
├── category.html
├── checkout.html
├── index.html
├── login.html
├── product-quickview.html
└── assets/
    ├── css/
    │   └── style.css
    └── images/
        └── *.webp
```

## Notes

This is a static UI prototype. Product data, authentication, cart persistence, payments, delivery tracking, and form submission are represented by the interface only and are not connected to a backend.

The project loads Tailwind CSS, Bootstrap Icons, and Google Fonts from public CDNs, so an internet connection is needed for the complete visual presentation. Product imagery and custom CSS are stored locally.
