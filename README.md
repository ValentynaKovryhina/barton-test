# Test task

A simple responsive portfolio-style landing page built with **Bootstrap** and **custom CSS** using the **BEM (Block Element Modifier)** naming convention.

---

## 🚀 Getting Started

### 📁 Folder Structure

```
project/
├── assets/
│   ├── images/
│   └── styles/
│       ├── normalize.css
│       └── style.css
├── index.html
└── README.md
```

---

## 🛠 Technologies Used

- **Bootstrap 5.3.3 (Grid & Reboot only)**
- **Google Fonts** (`Montserrat`, `Open Sans`)
- **Normalize.css**
- **Vanilla CSS**
- **BEM (Block Element Modifier) methodology** for class naming

Example:
```html
<div class="portfolio-card">
  <div class="portfolio-card__image">
    <img src="..." alt="..." />
  </div>
  <div class="portfolio-card__description">
    ...
  </div>
</div>
```

---

## 🔧 Setup & Development

1. Clone the repository or download the source code.
2. Open `index.html` in your browser.

> No build tools or bundlers are required — it's a static HTML project.

---

## 📦 CSS Naming Convention

This project uses the **BEM (Block Element Modifier)** methodology to keep the code organized and scalable.

- `block` — standalone component (`.portfolio-card`)
- `block__element` — part of a block (`.portfolio-card__image`)
- `block__element--modifier` — variant of an element (not shown in code, but supported)

---

## 📐 Layout & Styling

- The layout is powered by **Bootstrap Grid**.
- Custom styling is layered on top of Bootstrap with clear use of utility classes (`mt-3`, `px-2`, etc).
- Images use `object-fit: cover` and `aspect-ratio` techniques to maintain layout consistency.
- Mobile responsiveness is handled via Bootstrap’s responsive utilities and media queries.

---

## 📸 Images & Overlays

- Image blocks support a semi-transparent overlay using `::after` pseudo-elements.
- Aspect ratios and padding hacks are used for legacy browser support.

---

## 📝 License

This project is free to use and modify for personal or educational purposes.
