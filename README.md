# 🎨 Responsive CSS Lab

A structured collection of **CSS practice and projects** — covering everything from fundamentals to advanced layouts, animations, and fully responsive, real-world builds. Every folder represents one stage of progression, numbered in the order the concepts were explored.

---

## 📌 About This Repository

This repo is a personal CSS practice lab documenting the journey from basic styling to building responsive, production-style landing pages. It contains **90+ files** spanning concept demos, mini-projects, and complete responsive builds.

> **Styling approach across the journey:**
>
> - **Early modules (01–07):** Mostly **inline/internal CSS** inside HTML files — used for fast, isolated concept testing.
> - **Later modules (08–11):** **External CSS** files with a shared `assets/` structure — used to build clean, modular, industry-style projects including fully responsive layouts with media queries.

---

## 📂 Folder Structure

```
responsive-css-lab/
│
├── 01-basic-css/                  (16 files) – Selectors, units, inline/internal/external CSS
├── 02-background-properties/      (4 files)  – Backgrounds, gradients, blend modes
├── 03-box-model/                  (2 files)  – Box model & display property
├── 04-flex-model/                 (6 files)  – Flexbox layout system
├── 05-grid/                       (6 files)  – CSS Grid (parent & child properties)
├── 06-pseudo/                     (2 files)  – Pseudo-classes & pseudo-elements
├── 07-practice/                   (19 files) – Applied practice (cards, forms, navbars, galleries)
├── 08-small-projects/             (9 mini-projects) – Standalone CSS effect projects
├── 09-effects/                    (2 files)  – Transform & transition
├── 10-animation/                  (2 files)  – Keyframe animation, card flip
├── 11-responsive-projects/        (4 projects) – Full responsive builds with media queries
├── assets/
│   ├── css/                       (10 shared stylesheets)
│   └── images/                    (41 images/gifs used across demos)
└── README.md
```

---

## 🧩 Topics Covered

### 01. Basic CSS

Foundational styling concepts: `inline-css.html`, `internal-css.html`, `external.html`, `selectors.html`, `combinators.html`, `units-of-css.html`, plus early explorations of `position`, `overflow`, `box-shadow`, `drop-shadow`, `filters`, `list-properties`, and `column` layout.

### 02. Background Properties

`background_prop.html`, `linear_gradient.html`, `radial_gradient.html`, `blend-mode.html` — covering background positioning, gradients, and blend mode effects.

### 03. Box Model

`box-model.html`, `display_property.html` — content, padding, border, margin, and the `display` property behavior.

### 04. Flex Model

Full Flexbox coverage: `Flex_model.html`, `flex_item_prop.html`, `align_item.html`, `justify-content.html`, `flex-wrap.html`, and an applied `Practice_flexmodel.html`.

### 05. Grid

CSS Grid fundamentals split into parent vs. child properties: `grid.html`, `col_row.html`, `align_properties.html`, `justify_properties.html`, `template_areas.html`, `item_prop.html`.

### 06. Pseudo

`pseudo_classes.html` and `pseudo_elements.html` — `:hover`, `:nth-child`, `::before`, `::after`, etc.

### 07. Practice

The largest applied-practice set (19 files) — real UI patterns like `navbar.html`, `fixed-navigation-bar.html`, `form.html`, `table.html`, `profile_card.html`, `photo_gallery.html`, `homepage_grid.html`, `z-index.html`/`z-index_card.html`, `psd_effect.html`, `button.html`, `div_center.html`, `fonts-style.html`, and positioning/units drills.

### 08. Small Projects

Nine self-contained CSS effect demos, each in its own folder with paired HTML/CSS:

- **font-scroll** – scrolling gradient/glow text
- **icon-hover-effect** – hover interactions on icons
- **linear-gradient-effects** / **radial-gradient-effects** – gradient showcases
- **moon-animation** – CSS-only moon animation
- **myntra-landing-page** – e-commerce landing page clone
- **parallax-scrolling** – parallax background effect
- **running-landscape** – animated scene (runner, bird, sunrise)
- **transition-playground** – CSS transition experiments

### 09. Effects

`transform.html` and `transition.html` — 2D/3D transforms and transition timing.

### 10. Animation

`animation.html` (keyframes) and `card_flip.html` (3D flip using `perspective` and `transform-style`).

### 11. Responsive Projects ⭐

The most advanced module — real responsive builds using `@media` queries:

- **responsive-navbar** – navbar with mobile drawer/overlay behavior
- **image-carousel** – auto-sliding image carousel
- **background-image-slideshow** – CSS-animation-driven slideshow
- **flowsync-landing-page** – a full SaaS landing page clone (Linear/Vercel/Stripe-inspired), with its own `project-planning.md` defining a complete design system (color palette, typography scale, spacing, border-radius, shadows, and 5-tier responsive breakpoints from 375px to 1200px+). Sections built so far: Navbar, Hero, Trusted Companies, Features — with Pricing, Testimonials, FAQ, and Footer planned.

### assets/

Shared resources used across the modules and small projects:

- `css/` – 10 stylesheets (`style.css`, `flex_layout.css`, `transform.css`, `transition.css`, `animation.css`, `card_flip.css`, `overflow.css`, `psd_effect.css`, `z-index_card.css`, `fixed-navigation-bar.css`)
- `images/` – 41 images/GIFs (photos, icons, illustrations) used throughout the demos and mini-projects

---

## 💡 Key Takeaways

1. **Positioning & Flow** – Using `position: relative`/`absolute` to offset elements and establish containment contexts for child elements.
2. **CSS Units** – Choosing the right unit for fluid design: `rem` for typography, `%` for column scaling, `px` for fixed elements.
3. **Layout Systems** – Progressing from box-model basics → Flexbox → CSS Grid for increasingly complex layouts.
4. **Responsive Design** – Applying `@media` breakpoints (375px / 576px / 768px / 992px / 1200px+) to build layouts that adapt across devices, as demonstrated in the `11-responsive-projects/` module.
5. **Project Structure** – Moving from single-file inline demos to a modular `assets/css` + `assets/images` architecture suited for real projects.
6. **Design Systems** – The FlowSync project introduces a documented design system (colors, type scale, spacing, shadows) before implementation — a professional workflow habit.

---

## 🛠️ Tools Used

- **Code Editor:** Visual Studio Code
- **Version Control:** Git & GitHub
- **Local Server:** Live Server Extension (Port: 5500)
- **Tech Stack:** HTML5, CSS3 (no frameworks — vanilla CSS throughout)

---

## ▶️ How to View

1. Clone or open the folder in VS Code.
2. Open any `.html` file directly in a browser, or use the **Live Server** extension for auto-reload.
3. For the responsive projects (`11-responsive-projects/`), resize the browser window or use DevTools' device toolbar to see the media-query breakpoints in action.

---

## 👨‍💻 Author

**Laxman Singh**
Frontend Developer

Building modern, responsive, and interactive web interfaces. This repository showcases my CSS work — from core concepts to fully responsive, real-world projects.

---

## ⭐ Support

If you find this repository helpful, consider giving it a **⭐ Star** on GitHub.
