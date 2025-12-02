# 📘 **Oliver CSS Framework**

[![Version](https://img.shields.io/github/v/release/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/releases)
[![GitHub stars](https://img.shields.io/github/stars/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/network)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**Oliver CSS** (`cssoliver`) is a **lightweight modular CSS framework** built with clarity, scalability, and developer-friendliness in mind.
It includes a full set of utilities, layout tools, components, animations, and responsive helpers — all fully customizable using CSS variables.

---

# 📂 Folder Structure

```
src/
│
├─ reset.css
├─ variables.css
├─ typography.css
├─ layout.css
├─ animations.css
├─ responsive.css
├─ utilities.css          # (if you add utilities later)
│
├─ components/
│   ├─ buttons.css
│   ├─ cards.css
│   ├─ alerts.css
│   ├─ navbar.css
│   ├─ modals.css
│   └─ forms.css
│
└─ framework.css          # Imports everything above
```

Compiled output:

```
dist/
├─ oliver.css
└─ oliver.min.css
```

---

# ✨ Features

✔ **Modular file structure**
✔ **Utility-first approach** for spacing, text, colors, flex, grid
✔ **Prebuilt components** (buttons, cards, navbar, forms, alerts, modals)
✔ **CSS variables** for theming
✔ **Responsive grid system**
✔ **Animations & transitions**
✔ **Lightweight & fast**
✔ **Fully customizable**
✔ **Build system** with PostCSS, autoprefixer, and minification

---

# 🚀 Installation

## **Option 1 — Use the compiled CSS**

```html
<link rel="stylesheet" href="dist/oliver.min.css">
```

---

## **Option 2 — Install via npm**

```bash
npm install cssoliver
```

Then import:

```css
@import "cssoliver/dist/oliver.css";
```

---

## **Option 3 — CDN (after publishing to npm)**

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/cssoliver/dist/oliver.min.css">
```

---

# 🧩 Components

| Component | File                     | Description                        |
| --------- | ------------------------ | ---------------------------------- |
| Buttons   | `components/buttons.css` | Variants, sizes, full-width        |
| Cards     | `components/cards.css`   | Headers, footers, shadows          |
| Alerts    | `components/alerts.css`  | Success, warning, danger, info     |
| Navbar    | `components/navbar.css`  | Responsive nav, dark/light themes  |
| Modals    | `components/modals.css`  | Overlay, animations                |
| Forms     | `components/forms.css`   | Inputs, selects, textareas, groups |

---

# 🛠 Utilities

### Spacing

`m-0` → `m-5`
`p-0` → `p-5`

### Text

`text-center`, `text-light`, `text-uppercase`

### Colors

`bg-primary`, `text-danger`, `bg-light`

### Flex

`d-flex`, `justify-between`, `align-center`

### Borders & Shadows

`rounded`, `shadow-lg`, `border`

### Display

`hidden`, `block`, `inline-block`

---

# 📐 Layout & Grid System

* `.container`
* `.row`
* `.col`, `.col-6`, `.col-4`
* `.col-md-*`, `.col-lg-*`
* Flex-based grid

Example:

```html
<div class="row">
  <div class="col-12 col-md-6 col-lg-4">Column</div>
</div>
```

---

# 📱 Responsive Design

Breakpoints are mobile-first:

* `sm` – 480px
* `md` – 768px
* `lg` – 1024px
* `xl` – 1280px

Usage:

```html
<div class="p-2 p-md-4 p-lg-5">
  Responsive Padding
</div>
```

---

# 🎨 Theming (CSS Variables)

The framework uses variables for:

* Colors
* Spacing
* Typography
* Radius
* Shadows
* Transitions

Customize in `variables.css`.

Example:

```css
:root {
  --primary: #4a6cf7;
  --radius-md: 8px;
  --shadow: 0 4px 12px rgba(0,0,0,.1);
}
```

---

# 🧪 Development (Build System)

You can rebuild the framework using:

```bash
npm run build
```

Build tools:

* PostCSS
* Autoprefixer
* CSSNano (minification)

Output goes to `/dist`.

---

# 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit using conventional commits (recommended)
4. Submit a PR

Example: `1.0.0` → first stable release.

---

# 🗒 License

Released under the **MIT License**.
See the `LICENSE` file for details.