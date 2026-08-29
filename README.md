# 🎨 Responsive CSS Lab

A structured collection of **CSS practice, experiments, mini-projects, animations, effects, and responsive web builds** — covering everything from CSS fundamentals to advanced layouts and real-world responsive interfaces.

Every folder represents a stage of progression, numbered in the order the concepts were explored.

---

## 📌 About This Repository

This repository is a personal CSS learning lab documenting the journey from basic CSS concepts to building responsive, production-style interfaces.

It contains concept demonstrations, applied practice, CSS effects, animations, mini-projects, and complete responsive projects.

> **Styling approach across the journey:**
>
> - **Early modules (01–07):** Mostly inline/internal CSS inside HTML files for quick and isolated concept testing.
> - **Later modules (08–11):** More structured projects using external CSS, dedicated project folders, and reusable asset structures.
> - **Responsive projects (11):** Focused on building layouts that adapt across different screen sizes using CSS media queries.

---

## 📂 Folder Structure

```text
responsive-css-lab/
│
├── 01-basic-css/
├── 02-background-properties/
├── 03-box-model/
├── 04-flex-model/
├── 05-grid/
├── 06-pseudo/
├── 07-practice/
├── 08-small-projects/
├── 09-effects/
├── 10-animation/
│
├── 11-responsive-projects/
│   ├── background-image-slideshow/
│   ├── image-carousel/
│   ├── loader-animation/
│   ├── responsive-navbar/
│   └── login-ui/
│
├── assets/
│   ├── css/
│   └── images/
│
└── README.md
```

---

## 🧩 Topics Covered

### 01. Basic CSS

Covers the fundamentals of CSS and basic styling concepts, including:

- Inline CSS
- Internal CSS
- External CSS
- Selectors
- Combinators
- CSS units
- Positioning
- Overflow
- Box shadows
- Drop shadows
- Filters
- List properties
- Column layouts

---

### 02. Background Properties

Exploration of CSS background-related properties and visual effects:

- Background images
- Background positioning
- Linear gradients
- Radial gradients
- Blend modes

Example files include:

```text
background_prop.html
linear_gradient.html
radial_gradient.html
blend-mode.html
```

---

### 03. Box Model

Understanding how elements occupy space in a webpage:

- Content
- Padding
- Border
- Margin
- Box sizing
- Display property

Example files:

```text
box-model.html
display_property.html
```

---

### 04. Flex Model

Complete practice with the CSS Flexbox layout system.

Topics include:

- Flex container
- Flex items
- `flex-direction`
- `justify-content`
- `align-items`
- `flex-wrap`
- Flex item properties
- Practical Flexbox layouts

Example files:

```text
Flex_model.html
flex_item_prop.html
align_item.html
justify-content.html
flex-wrap.html
Practice_flexmodel.html
```

---

### 05. Grid

CSS Grid fundamentals covering both parent and child properties.

Topics include:

- Grid container
- Rows & columns
- Alignment properties
- Justification properties
- Template areas
- Grid item properties

Example files:

```text
grid.html
col_row.html
align_properties.html
justify_properties.html
template_areas.html
item_prop.html
```

---

### 06. Pseudo

Practice with CSS pseudo-classes and pseudo-elements.

Topics include:

- `:hover`
- `:nth-child()`
- `:focus`
- `::before`
- `::after`
- Other pseudo selectors

Example files:

```text
pseudo_classes.html
pseudo_elements.html
```

---

### 07. Practice

Applied CSS practice containing UI patterns and layout exercises.

Some examples include:

- Navigation bars
- Fixed navigation
- Forms
- Tables
- Profile cards
- Photo galleries
- Homepage layouts
- Z-index practice
- Buttons
- Centering elements
- Typography
- Positioning
- CSS units

This section focuses on applying previously learned CSS concepts to practical layouts.

---

## 08. Small Projects

A collection of standalone CSS mini-projects and visual effect experiments.

Projects include:

- **font-scroll** – Scrolling gradient/glow text
- **icon-hover-effect** – Hover interactions on icons
- **linear-gradient-effects** – Linear gradient effects
- **radial-gradient-effects** – Radial gradient effects
- **moon-animation** – CSS-only moon animation
- **myntra-landing-page** – E-commerce landing page clone
- **parallax-scrolling** – Parallax background effect
- **running-landscape** – Animated landscape scene
- **transition-playground** – CSS transition experiments

Each project focuses on practicing a specific CSS technique or visual effect.

---

## 09. Effects

This module focuses on CSS transformations and transitions.

Topics include:

- 2D transforms
- 3D transforms
- Scale
- Rotate
- Translate
- Skew
- Transition timing
- Transition effects

Example files:

```text
transform.html
transition.html
```

---

## 10. Animation

CSS animation practice using keyframes and 3D transformations.

Projects include:

### Animation

Practice with:

- `@keyframes`
- Animation duration
- Animation timing functions
- Animation delay
- Infinite animations

### Card Flip

A 3D card-flip animation using:

- `perspective`
- `transform`
- `transform-style`
- 3D rotation

Example files:

```text
animation.html
card_flip.html
```

---

# 11. Responsive Projects ⭐

The most advanced section of this CSS lab focuses on creating responsive interfaces using **CSS media queries, flexible layouts, and responsive design techniques**.

Current projects:

### 🔹 Responsive Navbar

A responsive navigation system featuring:

- Desktop navigation
- Mobile navigation
- Mobile drawer
- Overlay behavior
- CSS media queries
- Responsive layout adjustments

### 🔹 Image Carousel

A responsive image carousel using CSS techniques for:

- Image presentation
- Automatic sliding
- Responsive sizing
- Overlay effects

### 🔹 Background Image Slideshow

A CSS animation-based background slideshow demonstrating:

- `@keyframes`
- Background image transitions
- Animation timing
- Responsive background behavior

### 🔹 Loader Animation

A CSS-only dots loading animation demonstrating:

- Multiple animated elements
- `@keyframes`
- `animation-delay`
- Opacity transitions
- Size transitions
- Sequential loading effects

Project structure:

```text
loader-animation/
│
├── assets/
│   └── style.css
│
└── loading.html
```

---

## 📁 Assets

Shared resources used across different modules and projects.

```text
assets/
├── css/
└── images/
```

### CSS

Contains reusable stylesheets used by different practice modules and projects.

### Images

Contains images and GIFs used throughout the CSS demonstrations and mini-projects.

---

## 💡 Key Takeaways

### 1. CSS Units

Learning when to use different CSS units:

- `px` – fixed sizing
- `%` – relative sizing
- `rem` – scalable typography and spacing
- `vh` / `vw` – viewport-based sizing

### 2. Layout Systems

Progression from basic layouts to modern CSS layout systems:

```text
Box Model
    ↓
Flexbox
    ↓
CSS Grid
```

### 3. Responsive Design

Using:

```css
@media;
```

queries and flexible layouts to create interfaces that adapt across:

- Mobile
- Tablet
- Laptop
- Desktop

### 4. CSS Animations

Understanding:

- `transition`
- `transform`
- `@keyframes`
- `animation`
- `animation-delay`
- Timing functions

### 5. Project Structure

Progressing from simple single-file experiments toward organized project structures using:

```text
HTML
CSS
Assets
Images
```

This helps develop better habits for real-world frontend projects.

---

## 🛠️ Tools Used

- **Code Editor:** Visual Studio Code
- **Version Control:** Git & GitHub
- **Local Server:** Live Server Extension
- **Tech Stack:** HTML5 & CSS3
- **Frameworks:** None
- **CSS Approach:** Vanilla CSS

---

## ▶️ How to View

1. Clone or download this repository.
2. Open the repository in Visual Studio Code.
3. Open any `.html` file directly in a browser.
4. For a better development experience, use the **Live Server** extension.
5. For responsive projects, resize the browser window or use Chrome DevTools' device toolbar to test different screen sizes.

---

## 👨‍💻 Author

**Laxman Singh**
Frontend Developer

Building modern, responsive, and interactive web interfaces while continuously improving frontend development skills.

---

## ⭐ Support

If you find this repository useful or helpful for your own CSS learning journey, consider giving it a ⭐ **Star** on GitHub.
