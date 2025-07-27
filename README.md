# 📘 Spotlight Scroll 

A vertically scroll-triggered spotlight layout featuring animated feature cards with a sticky visual. Ideal for SaaS feature overviews or marketing pages.


---

## 🚀 Features

- Scroll-triggered card animations using `@keyframes + view-timeline`
- Sticky visual beside the animated feature stack
- Responsive layout using CSS container queries
- Card sections sized with `clamp()`, `cqi`, `cqh` for fluid geometry
- Scroll snapping for spotlight experience

---

## 🛠 Tech Stack

- **HTML5** — Semantic layout structure
- **CSS3** — Grid, Flexbox, animation, container queries
- **View Timeline API** — Scroll-triggered animations (experimental)
- **Modern CSS Units** — `cqi`, `cqh`, `clamp()`, `scroll-snap-align`, `position: sticky`

---

## 🧩 Layout Overview

| Section           | Purpose                          |
|-------------------|----------------------------------|
| `.feature-scroll` | Main scroll container            |
| `.feature-container` | Two-column flex layout         |
| `.feature-cards`  | Stack of scrollable feature cards |
| `.card-container` | Each card wrapper (100vh height) |
| `.card`           | Individual animated card         |
| `.side-visual`    | Sticky image section             |

---

## 📱 Responsiveness

- Uses `@container` queries to rearrange layout on smaller screens
- Visual moves below cards on mobile (`column-reverse`)
- Typography and layout units scale with screen width

---

## 🧪 Browser Support

- Works fully on **Chrome** and **Edge**
- `view-timeline` is experimental; not yet supported in Firefox or Safari
- Fallback: cards still scroll naturally without animation

---
## 🔗 Live Demo

🌐 [View Live Site](https://spotlight-scroll.vercel.app)
