# Oliver Framework (cssoliver)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/network)
[![Version](https://img.shields.io/github/v/release/xxVertex/cssoliver)](https://github.com/xxVertex/cssoliver/releases)

**Oliver Framework** (`cssoliver`) is a **lightweight, fully-featured CSS framework** designed for rapid web development and learning. It provides **modular utilities, responsive layouts, pre-built components, and customizable variables**, making it suitable for both beginners and professional developers.

---

## **Table of Contents**

* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Components](#components)
* [Utilities](#utilities)
* [Layout & Grid System](#layout--grid-system)
* [Responsive Design](#responsive-design)
* [Contributing](#contributing)
* [License](#license)

---

## **Features**

* **Lightweight and modular** — only include what you need
* **Utility classes** for spacing, colors, typography, flex, grids, and more
* **Responsive and mobile-first** design
* **Pre-designed components**: buttons, cards, alerts, forms, modals, navbar
* **Animations & transitions**: fade, slide, hover effects
* **Customizable via CSS variables**: colors, spacing, fonts, shadows, borders
* **Easy integration** with any HTML project

---

## **Installation**

Include the CSS in your project by linking the compiled framework file:

```html
<link rel="stylesheet" href="css/framework.css">
```

Or via npm/yarn:

```bash
npm install cssoliver
# or
yarn add cssoliver
```

Then import in your main CSS or SCSS file:

```css
@import "node_modules/cssoliver/css/framework.css";
```

---

## **Usage**

### **Buttons**

```html
<button class="btn btn-primary">Primary</button>
<button class="btn btn-outline">Outline</button>
```

### **Cards**

```html
<div class="card p-4 shadow rounded">
  <h3>Card Title</h3>
  <p>This is a card description.</p>
</div>
```

### **Utilities**

```html
<p class="text-center m-4 p-2 bg-primary text-light">Centered text with spacing</p>
```

---

## **Components**

* **Buttons:** `.btn`, `.btn-primary`, `.btn-outline`, `.btn-success`
* **Cards:** `.card`, `.card-header`, `.card-footer`
* **Alerts:** `.alert`, `.alert-success`, `.alert-danger`
* **Forms:** `.input`, `.select`, `.textarea`, `.form-group`
* **Modals:** `.modal`, `.modal-header`, `.modal-body`, `.modal-footer`
* **Navbar:** `.navbar`, `.nav-item`, `.nav-link`

---

## **Utilities**

* **Spacing:** `.m-1` to `.m-4`, `.p-1` to `.p-4`
* **Text:** `.text-center`, `.text-right`, `.text-uppercase`
* **Colors:** `.bg-primary`, `.text-success`, `.bg-light`
* **Display & Flex:** `.d-flex`, `.justify-center`, `.align-center`, `.flex-column`
* **Borders & Shadows:** `.rounded`, `.shadow`, `.border`
* **Visibility & Position:** `.hidden`, `.visible`, `.position-relative`, `.position-absolute`

---

## **Layout & Grid System**

* **Container:** `.container` for fixed-width or full-width layouts
* **Rows & Columns:** `.row`, `.col`, `.col-6`, `.col-4`
* **Flex Utilities:** `.d-flex`, `.justify-between`, `.align-center`
* **Responsive Helpers:** `.col-md-6`, `.col-lg-4`

---

## **Responsive Design**

Oliver Framework is **mobile-first** and includes built-in responsive breakpoints:

```html
<div class="col-12 col-md-6 col-lg-4">
  Responsive Column
</div>
```

* `col-12` → full-width on small screens
* `col-md-6` → half-width on medium screens
* `col-lg-4` → one-third width on large screens

---

## **Contributing**

We welcome contributions! Follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request

See the [GitHub repo](https://www.github.com/xxVertex/cssoliver) for more details.

---

## **License**

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.