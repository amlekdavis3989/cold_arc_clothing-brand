# COLD ARC — Next-Generation Alpine Wear Website

![COLD ARC](https://img.shields.io/badge/COLD%20ARC-FW%202025-D4895A?style=for-the-badge&labelColor=0D1520)
![HTML](https://img.shields.io/badge/HTML-Single%20File-E8EDF5?style=for-the-badge&labelColor=1A2332)
![Images](https://img.shields.io/badge/Images-29%20Embedded-A8C4D8?style=for-the-badge&labelColor=1A2332)

A fully self-contained, single-file premium alpine wear brand website. No server required — just open `cold-arc.html` in any modern browser.

---

## 🚀 Quick Start

```bash
# Simply open the file in your browser
open cold-arc.html

# Or drag and drop cold-arc.html into any browser window
```

No dependencies. No installation. No internet connection required after download.

---

## 📁 File Structure

```
cold-arc/
├── cold-arc.html       ← The entire website (5MB, fully self-contained)
└── README.md           ← This file
```

All 29 product/editorial images are embedded as base64 directly inside `cold-arc.html`. Nothing else is needed.

---

## ✨ Features

### 🛍️ E-Commerce
| Feature | Details |
|---|---|
| Product Catalog | 18 products with filter (All / Puffers / Shells / Accessories / Sale) and sort |
| Quick View | Modal with product image, description, feature list, size selector |
| Add to Cart | Instant cart update with toast notification |
| Cart Sidebar | Slides in from right — qty controls, remove, live subtotal |
| 3-Step Checkout | Shipping → Payment → Review → Order Confirmed |
| Payment Methods | Credit Card form, Apple Pay, PayPal options |
| Shipping Options | Standard (free over $500), Express ($25), Next Day ($50) |
| Tax Calculation | Auto 8.5% tax applied at checkout |

### 👤 Login / Account
| Feature | Details |
|---|---|
| Sign In | Email + password form |
| Register | Full name, email, password |
| Google Sign-In | One-click button (UI only) |
| Session State | Nav bar updates to show username after login |

### 🖼️ Gallery
| Feature | Details |
|---|---|
| Masonry Grid | 9-photo responsive grid layout |
| Lightbox | Fullscreen viewer with prev/next navigation |
| Hover Effects | Zoom + brightness + "View Full" overlay |

### ❓ Help Center
| Tab | Content |
|---|---|
| FAQ | 7 expandable questions covering shipping, returns, sizing, warranty, care |
| Contact Us | Direct email link + contact form (name, email, subject, message) |
| Track Order | Order number lookup UI |

**Contact email:** `amalekdavis3989@gmail.com`

### 🎨 Design & UX
- Custom animated cursor (dot + lagging ring)
- Snow particle animation (50 particles)
- Hero background parallax zoom
- Scroll-triggered fade-up animations (IntersectionObserver)
- Horizontal scrolling lookbook
- Floating Help button (bottom right)
- Toast notifications on cart actions

---

## 🗂️ Site Sections

1. **Fixed Navigation** — Logo, links, Help, Sign In, Cart with live badge
2. **Hero** — Full-screen editorial background, stats (−40° / 20K / 850), dual CTAs
3. **Ticker** — Continuous scrolling marquee
4. **Featured Banner** — H Landing Jacket hero drop
5. **Catalog** — 18-product grid with filters and sort
6. **Features Strip** — 4 technology pillars
7. **Gallery** — 9-photo masonry grid with lightbox
8. **Layering System** — 4-layer visual guide (Base / Mid / Shell / Storm)
9. **Editorial** — Manifesto + brand stats + two editorial panels
10. **Cold Up North Banner** — Full-width cinematic strip
11. **Tech Specs** — Annotated jacket diagram + spec table with bar fills
12. **Lookbook** — 8-card horizontal scroll with hover effects
13. **Footer** — Brand info, shop/brand/contact links, legal

---

## 🎨 Brand Design System

### Color Palette
```css
--ice:     #E8EDF5   /* Light blue-white */
--glacier: #A8C4D8   /* Glacier blue */
--snow:    #F2F5FA   /* Pure snow */
--steel:   #4A6175   /* Steel blue-gray */
--slate:   #1A2332   /* Dark slate */
--deep:    #0D1520   /* Near-black deep */
--frost:   #C5D8E8   /* Frost blue */
--accent:  #D4895A   /* Warm sunset orange */
--accent2: #7FAEC8   /* Soft glacier */
--red:     #C44B30   /* Sale / alert red */
```

### Typography
| Role | Font | Usage |
|---|---|---|
| Display / Headlines | Bebas Neue | Section titles, product names, prices |
| Body / UI | DM Sans | Descriptions, form inputs, paragraphs |
| Labels / Mono | Space Mono | Tags, nav links, metadata, specs |

---

## 🖼️ Images Used (29 total)

### Original Series (10)
| ID | Description | Placement |
|---|---|---|
| IMG1 | Skier action at sunset | Hero fallback, lookbook |
| IMG2 | Mountains poster | Catalog |
| IMG3 | Fur coat woman running snow | Catalog, editorial |
| IMG4 | Athlete goggles closeup | Catalog, accessories |
| IMG5 | White puffer woman snow | Hero fallback, catalog |
| IMG6 | Cinematic mountain banner | Cold Up North strip |
| IMG7 | FRZN thank you editorial | Editorial panel |
| IMG8 | Urban puffer man | Catalog, lookbook |
| IMG9 | Minimal puffer mockup | Catalog, tech specs, layering |
| IMG10 | Ski snow poster | Lookbook |

### New Series 1 (10)
| ID | Description | Placement |
|---|---|---|
| N1 | North Face layering system | Layering system |
| N2 | Arc'teryx mountain dramatic | Featured banner, catalog, lookbook |
| N3 | Welter Experiment field jacket | Catalog, layering |
| N4 | Homme winter puffer editorial | Catalog, lookbook |
| N5 | Goldwin Gore-Tex red editorial | Editorial panel |
| N6 | Eider rust anorak back view | Catalog, lookbook |
| N7 | Gore-Tex Infinium green | Catalog, layering |
| N8 | Lone figure dramatic mountain | Editorial bg, catalog |
| N9 | Eider white performance jacket | Catalog, layering |
| N10 | Goldwin red rain shell | Editorial panel |

### New Series 2 (9)
| ID | Description | Placement |
|---|---|---|
| X1 | Sunset silhouette hood | Editorial panel, lookbook |
| X2 | Red glowing night figure | Catalog, editorial bg |
| X3 | Rain storm model goggles | Hero background, lookbook |
| X4 | Gorpcore Arc'teryx B&W | Gallery, catalog, lookbook |
| X5 | Mountain ninja Italy | Gallery, catalog, lookbook |
| X6 | Ski helmet B&W | Gallery, catalog, lookbook |
| X7 | Anonymous rider orange goggle | Gallery, editorial panel |
| X8 | H Landing Jacket summit | Featured banner, tech specs, catalog |
| X9 | Color-graded fashion editorial | Gallery, lookbook |

---

## 🛠️ Technical Details

- **Stack:** Pure HTML + CSS + Vanilla JavaScript
- **External resources:** Google Fonts only (loaded from CDN)
- **File size:** ~5MB (all images base64 embedded)
- **Browser support:** All modern browsers (Chrome, Firefox, Safari, Edge)
- **No frameworks:** No React, Vue, jQuery, or Bootstrap
- **No backend:** Static file — works completely offline

### JavaScript Modules (all inline)
- Product data array (18 products)
- Cart state management
- Login state management
- Gallery lightbox
- Checkout multi-step flow
- FAQ accordion
- Contact form handler
- Cursor animation loop
- Snow particle generator
- IntersectionObserver scroll animations

---

## 📧 Contact

For support or inquiries: **amalekdavis3989@gmail.com**

---

## 📝 Customization Guide

### Add a new product
In the `products` array inside the `<script>` tag:
```javascript
{
  id: 19,                        // unique ID
  name: 'Product Name',
  series: 'Series Name',
  price: 999,
  oldPrice: null,                // or a number for sale price
  badge: 'New',                  // 'New', 'Sale', 'Ltd', or null
  cat: 'shell',                  // 'shell', 'puffer', or 'accessories'
  img: 'data:image/jpeg;base64,...',  // base64 image
  desc: 'Product description.',
  features: ['Feature 1', 'Feature 2', 'Feature 3']
}
```

### Change contact email
Search for `amalekdavis3989@gmail.com` in the HTML and replace with your email address (appears 3 times).

### Update brand colors
Edit the `:root` CSS variables at the top of the `<style>` block.

### Add gallery images
Add base64 image strings to the `galleryImgs` array in the script, and add corresponding labels to the `labels` array inside `buildGallery()`.

---

*© 2025 COLD ARC. All rights reserved.*
