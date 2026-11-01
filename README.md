# 🛒 LITTLECART

A neon-lit mini online store for shirts, jeans, shoes and watches. It is a single HTML file, so there is nothing to install and nothing to build.

![Littlecart screenshot](screenshot.png)

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

---

## Features

- Four categories: Shirts, Jeans, Shoes and Watches
- Separate stock for every product, with a stock bar and "Only N left" / "Sold out" states
- Quantity picker that never goes above the available stock
- Basket with per-item quantity: remove one unit, remove an item, or clear everything
- Coupon code (20% off) that changes every visit
- Live subtotal, discount and total in Indian digit grouping (₹2,00,00,000)
- Order receipt, and stock is deducted when the order is placed
- Neon cyberpunk design with a sign that lights up on load (respects reduced-motion settings)
- Responsive layout for phones and desktops

## Run it

Download the file and open `index.html` in any browser. That's it.

> The page loads the Tilt Neon and Sora fonts from Google Fonts, so you need an internet connection for the exact look. It still works without them, using fallback fonts.

## Host it free on GitHub Pages

1. Push the repo to GitHub with the file named `index.html`.
2. Go to **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the `/ (root)` folder, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` in a minute or two.

## How the coupon works

A code like `DIWALI4821` is generated every time the page loads and is shown at the top. Enter it in the basket to get 20% off. Matching is not case-sensitive. Stock levels are also random on each visit, and the **Restock shelves** button at the bottom resets everything.

## Tech stack

- HTML, CSS and vanilla JavaScript, all in one file
- Google Fonts: Tilt Neon and Sora

## Project structure

```
.
├── index.html
├── screenshot.png
└── README.md
```

## Ideas for later

- Search and price filters
- Saving the basket with `localStorage`
- Real product images
- Payment gateway integration

## License

MIT License. Add a `LICENSE` file if you want to use this.

---

Made by `<your-name>`
