# 🌐 Alex Band — Portfolio Website

A simple, responsive portfolio website to present my background and showcase selected projects.  
Built with **HTML**, **CSS**, and a small amount of **vanilla JavaScript** for the mobile navigation toggle.

---

## 🔗 Live
(Add your live URL here if deployed, e.g. Netlify/GitHub Pages.)

---

## 📦 Tech Stack
- **HTML5** — semantic sections for intro, services, about, projects, and footer
- **CSS3** — custom styles + responsive layout
- **JavaScript (vanilla)** — hamburger button to toggle the navigation (`.nav-toggle`)
- **Normalize.css** — cross-browser CSS reset
- **Font Awesome** — social icons in the footer
- **Google Fonts** — Lora & Roboto Slab typography

CDN assets used:
- `normalize.css`
- `font-awesome` (5.11.2)
- Google Fonts: `Lora`, `Roboto Slab`

---

## 🧭 Site Structure (Sections)
- **Header / Navigation**
  - Hamburger button (`.nav-toggle`) with `aria-label="toggle navigation"`
  - Links to `#home`, `#services`, `#about`, `#work`

- **Intro (`#home`)**
  - Title: “Hi, I am **Alex Band**”
  - Subtitle: “Front-End Developer”
  - Hero image: `img/hero-img.jpeg`

- **My Services (`#services`)**
  - “What I do” with two service cards:
    - **Fundamentals** — HTML, CSS, JavaScript, REST APIs
    - **React** — Router, component architecture, state, authentication
  - CTA button to “My Projects”

- **About Me (`#about`)**
  - Subtitle: “Front-End Developer and cat lover based in Mexico”
  - Two-paragraph bio
  - Image: `img/desc-img.jpeg`

- **My Projects (`#work`)**
  - Subtitle: “A selection of my range of work”
  - Portfolio grid linking to individual project pages:
    - `portfolio-item-dashboard.html` — thumb: `img/dashboard-project-img.png`
    - `portfolio-item-tenzies.html` — thumb: `img/tenzies.jpg`
    - `portfolio-item-assembly.html` — thumb: `img/assembly-game-img.png`
    - `portfolio-item-zero-gravity-code.html` — thumb: `img/my-site-port-thumb.png`
    - `portfolio-item-expense-tracker.html` — thumb: `img/expense-tracker-port-thumb.png`
    - `portfolio-item-landing-page.html` — thumb: `img/lead-gen-page-port-thumb.png`

- **Footer**
  - Email: `alexband1996dev@gmail.com`
  - Social links: Facebook, LinkedIn, X (Twitter), GitHub

---

## ▶️ Getting Started (Local)
1. Clone or download this repo.
2. Open `index.html` in your browser.
3. Ensure the `/img` assets and `style.css` are in the expected locations.

_No build step required; this is a static site._

---

## 📁 Files of Note
- `index.html` — main page
- `style.css` — styles
- `index.js` — nav toggle logic
- `/img/*` — hero, about, and project thumbnails
- `portfolio-item-*.html` — individual project pages

---

## 📝 Accessibility & Semantics
- Uses semantic headings and section landmarks.
- Mobile navigation has an accessible toggle button with `aria-label`.
- Provide meaningful `alt` text for images (consider updating any placeholder alt text).

---

## ✅ To Do / Improvements (nice-to-have)
- Deduplicate multiple `normalize.css` links in `<head>`
- Add a meta description for SEO
- Consider keyboard handling / focus styles for the nav toggle
- Add Open Graph/Twitter meta tags for rich link previews

---

## 📸 (Optional) README Preview
If this repo is public and contains images, you can embed a preview:

```md
![Hero](img/hero-img.jpeg)
