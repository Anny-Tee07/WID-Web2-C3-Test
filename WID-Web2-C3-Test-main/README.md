# NovaSpark — Responsive Landing Page

A responsive landing page built as part of the **WID Web2 C3 Frontend Evaluation Test**.

---


## 📌 Project Overview

This project is a single-file responsive landing page for a fictional digital product studio called **NovaSpark**. It was built using semantic HTML5 and native CSS — no frameworks, no external stylesheets.

---

## 🧩 Sections Included

- **Navigation** — Fixed responsive navbar with hamburger menu for mobile
- **Hero** — Headline, description, and two call-to-action buttons
- **Features** — 6 service cards with hover effects and scroll animations
- **Stats** — 4 key business metrics
- **Testimonials** — 3 client testimonial cards
- **CTA Banner** — Full-width call-to-action section
- **Footer** — Brand info, navigation links, and social media icons

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantics |
| Native CSS | All styling (inside `<style>` tag) |
| Vanilla JavaScript | Scroll reveal, sticky nav, hamburger menu |
| Google Fonts | Playfair Display + DM Sans |

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| Desktop (1024px+) | 3-column features grid, 4-column footer |
| Tablet (768px–1024px) | 2-column features grid, 2-column footer |
| Mobile (< 768px) | Single column, hamburger nav |

---

## ✨ Features & Highlights

- Single `index.html` file — no external CSS or JS files
- Scroll-triggered entrance animations via `IntersectionObserver`
- Accessible markup with ARIA labels and semantic HTML
- Sticky nav with blur backdrop that reacts to scroll position
- CSS custom properties (design tokens) for consistent theming
- Smooth hover transitions on cards, buttons, and nav links

---

## 📂 Project Structure

```
WID-Web2-C3/
├── index.html       # All HTML, CSS, and JS in one file
└── README.md        # Project documentation
```

---

## 🚀 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/WID-Web2-C3.git
   ```
2. Navigate into the project folder:
   ```bash
   cd WID-Web2-C3
   ```
3. Open `index.html` in your browser — no build step needed.

---

## 🌐 Deployment

This project can be deployed on any static hosting platform:

- **GitHub Pages** — Push to `main` and enable Pages in repo settings
- **Netlify** — Drag and drop the `index.html` file
- **Vercel** — Import the repo and deploy instantly


---

## 📄 License

This project was created for evaluation purposes as part of the WID Web2 C3 programme.