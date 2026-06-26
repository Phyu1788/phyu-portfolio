# Bloom & Petal — Florist E-Commerce Website

A beautiful, responsive single-page flower shop website built with React and Vite. Browse bouquets, arrangements, and single stems, add them to your cart, and enjoy a seamless shopping experience.

## Features

- **Product Catalog** — 8 curated flower products across 3 categories (Bouquet, Arrangement, Single)
- **Search & Filter** — Find products by name or browse by category
- **Product Detail Modal** — Click any product for expanded info and quick add-to-cart
- **Shopping Cart** — Add/remove items, adjust quantities, view totals, with `localStorage` persistence
- **Responsive Design** — Fully mobile-friendly with hamburger menu
- **Contact Form** — Reach out with a simulated submission flow
- **Smooth Navigation** — Scroll-based active section highlighting

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 19 |
| Build Tool | Vite 8 |
| Language | JavaScript (JSX) |
| Styling | Plain CSS with CSS variables |
| State | React Context API |
| Persistence | `localStorage` |
| Fonts | Google Fonts (Dancing Script, Playfair Display, Inter) |

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm

### Installation

```bash
# Clone the repository
git clone <repo-url>
cd florist

# Install dependencies
cd florist
npm install
```

### Development

```bash
npm run dev
```

Starts the Vite dev server with hot module replacement (HMR). Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build

```bash
npm run build
```

Produces an optimized production build in the `dist/` directory.

### Preview

```bash
npm run preview
```

Serves the production build locally for testing.

### Lint

```bash
npm run lint
```

Runs ESLint to check for code quality issues.

## Project Structure

```
florist/
├── index.html                  # SPA entry point
├── package.json
├── vite.config.js
├── eslint.config.js
├── public/
│   ├── favicon.svg
│   └── icons.svg
└── src/
    ├── main.jsx                # React root mount
    ├── App.jsx                 # Top-level layout and state
    ├── index.css               # Global styles and CSS variables
    ├── components/
    │   ├── Header.jsx          # Navigation bar + announcement bar
    │   ├── Hero.jsx            # Landing hero section
    │   ├── ProductGrid.jsx     # Searchable product listing
    │   ├── ProductCard.jsx     # Individual product tile
    │   ├── ProductDetail.jsx   # Product detail modal
    │   ├── CartPage.jsx        # Shopping cart modal
    │   ├── About.jsx           # Brand story section
    │   ├── Contact.jsx         # Contact form + info
    │   └── Footer.jsx          # Site footer
    ├── context/
    │   └── CartContext.jsx     # Cart state management
    ├── data/
    │   └── products.js         # Static product catalog
    └── assets/
        └── hero.png
```

## License

This project is for educational/portfolio purposes.
