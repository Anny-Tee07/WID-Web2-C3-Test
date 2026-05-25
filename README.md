# Ogechi Welechi — Personal Portfolio Landing Page

A responsive personal portfolio landing page built with **HTML** and **Tailwind CSS**, showcasing my work as a Business Developer and Growth Strategist across Web3 and African fintech.

---

## 🌐 Live Preview

> https://wid-web2-c3-test-ten.vercel.app/

---

## 📌 About This Project

This project was built as part of a frontend evaluation test. The goal was to create a fully responsive, single-file portfolio landing page using only HTML and Tailwind CSS — no separate CSS files, no JavaScript frameworks.

The page reflects my professional identity as a business developer, growth strategist, and tech-savvy operator — featuring my current roles at **Planbok** and **Women in DeFi**.

---

## 🗂️ Project Structure

```
WID-WEB2-C3-Test
├── index.html            # The entire page — all HTML and Tailwind classes in one file
├── assets                # Images used
│   ├── planbok-logo.png  # Planbok company logo (used in the Experience section)
│   ├── logo.png          # Personal/brand logo (used in the navbar and footer)
└── README.md             # This file
```

> All styling is done using Tailwind CSS utility classes directly in the HTML. There is no separate `.css` file.

---

## ✨ Features

- **Fully responsive** — works on mobile, tablet, and desktop
- **Single file** — everything lives in `index.html` as required
- **Tailwind CSS only** — no custom CSS frameworks or component libraries
- **Smooth scroll navigation** — navbar links scroll to their sections
- **Animated hero text** — gradient shimmer effect on the headline
- **Live Server compatible** — instant browser preview on every save
- **Accessible** — semantic HTML tags and descriptive `alt` attributes on all images

---

## 📄 Page Sections

| Section          | Description                                                                                          |
| ---------------- | ---------------------------------------------------------------------------------------------------- |
| **Navigation**   | Fixed top navbar with logo, section links, and a CTA button                                          |
| **Hero**         | Headline, bio, call-to-action buttons, and four key stat cards                                       |
| **Experience**   | Detailed cards for Planbok (Business Developer) and Women in DeFi (Marketing Lead)                   |
| **Skills**       | Six core skill cards covering BD, growth, marketing, tech communication, market entry, and community |
| **Testimonials** | Three client/colleague quotes plus a stats bar                                                       |
| **Contact**      | Email and LinkedIn CTA with social links                                                             |
| **Footer**       | Logo, copyright, and role description                                                                |

---

## 🛠️ Built With

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) — page structure and content
- [Tailwind CSS](https://tailwindcss.com/) — utility-first styling via CDN
- [Google Fonts](https://fonts.google.com/) — DM Serif Display (headings) and DM Sans (body)

---

## 📱 Responsiveness

The page is designed **mobile-first**. Tailwind's responsive prefixes are used throughout:

| Prefix   | Breakpoint | Device           |
| -------- | ---------- | ---------------- |
| _(none)_ | 0px+       | Mobile (default) |
| `sm:`    | 640px+     | Large mobile     |
| `md:`    | 768px+     | Tablet           |
| `lg:`    | 1024px+    | Desktop          |

Example from the experience grid:

```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6"></div>
```

This renders as 1 column on mobile, 2 on tablet, and 3 on desktop.

---

## 🔄 Git Workflow (Fork & Pull Request)

This project was submitted via GitHub's fork and pull request workflow:

1. **Forked** the original repository from the evaluator's GitHub account
2. **Cloned** the fork locally:
   ```bash
   git clone https://github.com/OgechiWelechi/repo-name.git
   cd repo-name
   ```
3. **Created** `index.html` from scratch in VS Code
4. **Staged and committed** the work:
   ```bash
   git add index.html
   git add README.md
   git commit -m "Add portfolio landing page - Ogechi Welechi"
   ```
5. **Pushed** to the fork:
   ```bash
   git push origin main
   ```
6. **Opened a Pull Request** from the fork back to the original repository

---

## 👩🏾‍💼 About Me

**Ogechi Welechi** is a Business Developer and Growth Strategist working at the intersection of technology, finance, and community across Africa.

- 🏢 **Business Developer** at [Planbok](https://planbok.com) — programmable multi-chain wallet infrastructure for African businesses
- 🌍 **Marketing Lead** at Women in DeFi — empowering women to lead in decentralised finance
- 📍 Based in Nigeria | Working across Nigeria, Ghana, and Kenya

---

## 📬 Contact

- **Email:** welechi.ogechi@gmail.com

---

_Built with HTML & Tailwind CSS · © 2026 Ogechi Welechi_
