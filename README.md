# Abhinav Kumar — Portfolio

A premium dark-themed personal portfolio built with **React**, **HTML**, and **CSS**.

---

## 🚀 Getting Started

### Prerequisites
- Node.js v16+ installed
- npm or yarn

### Installation & Run

```bash
# 1. Go into the project folder
cd abhinav-portfolio

# 2. Install dependencies
npm install

# 3. Start development server
npm start
```

Opens at **http://localhost:3000**

### Build for Production

```bash
npm run build
```

Generates optimized files in the `/build` folder — ready to deploy on Netlify, Vercel, or GitHub Pages.

---

## 📁 Project Structure

```
abhinav-portfolio/
├── public/
│   └── index.html          ← HTML entry point
├── src/
│   ├── components/
│   │   ├── Cursor.js / .css       ← Custom animated cursor
│   │   ├── Navbar.js / .css       ← Fixed top navigation
│   │   ├── Hero.js / .css         ← Full-screen hero with canvas animation
│   │   ├── Marquee.js / .css      ← Scrolling skills ticker
│   │   ├── About.js / .css        ← About + info grid
│   │   ├── Education.js / .css    ← Timeline with stagger animation
│   │   ├── Skills.js / .css       ← 3×2 skills grid
│   │   ├── Projects.js / .css     ← Project cards
│   │   ├── Activities.js / .css   ← Leadership/activities list
│   │   ├── Contact.js / .css      ← Contact section
│   │   └── Footer.js / .css       ← Footer
│   ├── styles/
│   │   └── global.css             ← CSS variables, reset, animations
│   ├── App.js                     ← Root component
│   └── index.js                   ← React entry point
└── package.json
```

---

## ✨ Features

- **Animated Canvas Hero** — live circuit constellation with mouse interaction & glowing signal particles
- **Custom Cursor** — dual-layer animated cursor with hover effects
- **Scroll Reveal** — elements animate in as you scroll
- **Education Timeline** — staggered entrance animation
- **Fully Responsive** — works on mobile and desktop
- **Pure CSS Variables** — easy to retheme (change `--accent` color in `global.css`)

---

## 🎨 Customization

All brand colors are in `src/styles/global.css` under `:root`:

```css
:root {
  --accent:  #e8ff47;   /* Yellow-green highlight */
  --purple:  #7b5cf0;   /* Purple accent */
  --bg:      #0a0a0f;   /* Dark background */
}
```

To update personal info, edit the data arrays in each component file.

---

## 🌐 Deploy on Netlify (Free)

1. Run `npm run build`
2. Go to [netlify.com](https://netlify.com) → Drag & drop the `/build` folder
3. Your site is live! ✅
