# projects
#  BRAISE — Fictional Gastronomic Restaurant Landing Page

A dark, luxury single-page landing page for a fictional 2-Michelin-star Parisian restaurant, built with **pure HTML & CSS** (no frameworks, no dependencies).

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

---

## Preview

> *A refined, dark-toned restaurant website featuring copper & gold accents, editorial typography, and smooth scroll animations.*

---

## Features

- **Single file** — everything lives in one `restaurant-landing.html` file (HTML + CSS + JS)
- **Custom cursor** — copper dot with a lagging ring follower
- **Scroll-triggered animations** — elements reveal as you scroll using `IntersectionObserver`
- **Sticky navigation** — solidifies with backdrop blur on scroll
- **Interactive menu tabs** — switch between menu categories
- **Reservation form** — date picker, guest count selector, dietary notes
- **SVG plate illustration** — hand-coded decorative plate artwork
- **Fully responsive-ready layout** — grid-based structure
- **No dependencies** — zero npm, zero frameworks, zero build step

---

##  Project Structure

```
braise-restaurant/
│
├── restaurant-landing.html   # The entire project (HTML + embedded CSS + JS)
└── README.md                 # This file
```

---

##  Getting Started

### Option 1 — Open directly in your browser

```bash
git clone https://github.com/YOUR_USERNAME/braise-restaurant.git
cd braise-restaurant
open restaurant-landing.html   # macOS
# or
start restaurant-landing.html  # Windows
# or
xdg-open restaurant-landing.html  # Linux
```

### Option 2 — Serve locally with a simple server

```bash
# Python 3
python -m http.server 8080

# Node.js (npx)
npx serve .
```

Then visit `http://localhost:8080/restaurant-landing.html`

---

##  Design Decisions

| Choice | Detail |
|---|---|
| **Color palette** | Near-black `#0a0806`, deep brown `#1a110a`, copper `#b5622a`, gold `#c9973f`, cream `#f2e8d9` |
| **Display font** | [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) — elegant, high-contrast serif |
| **Body font** | [Josefin Sans](https://fonts.google.com/specimen/Josefin+Sans) — geometric, ultra-light sans-serif |
| **Aesthetic** | Dark luxury / editorial — inspired by haute cuisine and high-end hospitality branding |
| **Animations** | CSS keyframes for hero entrance, JS `IntersectionObserver` for scroll reveals |

---

##  Sections

1. **Hero** — Full-screen intro with restaurant name, description, SVG plate art, and Michelin badge
2. **Concept** — Chef biography and key stats grid (seats, menu courses, wine list, stars)
3. **Menu** — 6 signature dishes with prices and tabbed navigation
4. **Gallery** — Four-panel space showcase with geometric SVG illustrations
5. **Reservation** — Contact form with date, guest count, and dietary preferences
6. **Footer** — Address, phone, email, social links

---

##  Deploy to GitHub Pages

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Click **Save** — your site will be live at:

```
https://YOUR_USERNAME.github.io/braise-restaurant/restaurant-landing.html
```

---

##  Customization

All design tokens are defined as CSS variables at the top of the `<style>` block:

```css
:root {
  --noir:       #0a0806;
  --brun:       #1a110a;
  --cuivre:     #b5622a;   /* copper — primary accent */
  --or:         #c9973f;   /* gold — secondary accent */
  --creme:      #f2e8d9;   /* main text color */
  --creme-pale: #faf6f0;
  --fumee:      #6b5b4e;
}
```

Change these to instantly re-theme the entire page.

---


##  Credits

- Fonts via [Google Fonts](https://fonts.google.com)
- Restaurant concept, content, and all code: fictional & original
- Built as a frontend design exercise — not affiliated with any real establishment
