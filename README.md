# Tanora Luxury Personal Care — HTML Showcase

Multi-page static showcase website for Tanora's 3 signature products:

- **Anti Hair Fall Shampoo**
- **Gentle Facewash**
- **Nourishing Conditioner**

## Pages (3 main screens + supporting)
- `index.html` — Homepage (hero, product grid with quick buy buttons, benefits, ingredients, reviews, CTA)
- `shampoo.html`, `facewash.html`, `conditioner.html` — Full product detail pages featuring:
  - Clickable image gallery + lightbox with zoom (click image to enlarge, click enlarged to zoom 2x)
  - Price, description, key ingredients
  - Direct **Amazon** & **Flipkart** purchase buttons (showcase only — no in-site checkout)
  - Customer reviews & ratings
  - Related products + combo highlights
- `combos.html` — 3 curated bundles with savings callouts + FAQ accordion
- `privacypolicy.html` — Updated legal page

## External Purchase Links
All "Buy" buttons link to Amazon.in / Flipkart search pages using placeholder queries.
**Replace the href values** with your actual product ASIN / Flipkart URLs when live.

Example:
```html
<a href="https://www.amazon.in/dp/B0YOURASIN" ...>BUY ON AMAZON</a>
```

## Design
- Premium dark luxury aesthetic (existing CSS preserved + extended)
- Fully responsive
- No frameworks — vanilla HTML + CSS + minimal JS
- Font Awesome icons + Google fonts (Cormorant Garamond + Inter)

## Running locally
Simply open `index.html` in any modern browser. No build step required.

## Notes
- Images: Currently using existing assets. Add `conditioner.jpg` or additional gallery shots as needed.
- Prices shown are illustrative.
- This is a **showcase only**. All sales are redirected to Amazon/Flipkart.

© 2026 Tanora Care
