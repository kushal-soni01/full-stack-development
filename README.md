<div align="center">

# 🚀 Full-Stack Development

### A hands-on learning journey through modern web development

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<br/>

*Building beautiful, responsive, and interactive web experiences — one concept at a time.*

---

</div>

## 📖 About

This repository is a collection of **practical exercises and mini-projects** built while learning full-stack web development. Each folder focuses on a specific CSS/HTML/JS concept, progressing from fundamentals to more advanced techniques like CSS Grid layouts, conic-gradient clocks, and dashboard UIs.

## 🗂️ Project Structure

```
Full-stack/
│
├── task1-2/          🔐 Login Card & Navbar
├── task3/            🛒 Product Cards (Flexbox)
├── task4/            📊 Admin Dashboard
├── bento/            🍱 Bento Grid Layouts
├── box-shadow/       🌑 Box Shadow & Text Shadow
├── gradients/        🎨 CSS Gradients & Animated Clock
├── positioning/      📌 CSS Positioning & Sticky Cards
└── DOM/              🧩 DOM Manipulation & Styling
```

---

## ✨ Modules

### 🔐 Task 1-2 — Login Card & Navbar

> A centered login form with a responsive navigation bar and product listing section.

| Concept | Details |
|---------|---------|
| **Flexbox Centering** | Vertically & horizontally centered login card |
| **Navigation Bar** | Logo + links with hover underline effects |
| **Sign-in Button** | Styled CTA with rounded corners |
| **Product Cards** | Three product cards with image, price & buy button |

**Files:** `index.html` · `style.css`

---

### 🛒 Task 3 — Product Cards (Flexbox)

> Responsive product card layout using Flexbox with `flex-wrap` for adaptive columns.

| Concept | Details |
|---------|---------|
| **Flexbox Layout** | `space-evenly` distribution with wrapping |
| **Card Design** | Bordered cards with padding and rounded corners |
| **Image Handling** | Auto-centered product images |

**Files:** `task3.html` · `style3.css`

---

### 📊 Task 4 — Admin Dashboard

> A full admin dashboard layout with sidebar navigation, stat cards, and a recent orders table.

| Concept | Details |
|---------|---------|
| **Sidebar Layout** | Fixed dark sidebar with navigation links |
| **Stat Cards** | Four metric cards (Revenue, Expenditure, Profit, Loss) |
| **Data Table** | Recent orders table with product, amount & status columns |
| **CSS Nesting** | Modern CSS nesting for scoped styles |

**Files:** `index.html` · `style.css`

---

### 🍱 Bento — Grid Layouts

> Two CSS Grid exercises exploring `grid-template-areas` and responsive bento-style layouts.

| Concept | Details |
|---------|---------|
| **Grid Template Areas** | Named grid areas for semantic layouts |
| **Responsive Grid** | `@media` query rearranges grid at 500px breakpoint |
| **Bento Layout** | Dashboard-style layout with header, sidebar, content, footer |
| **auto-fit / minmax** | Fluid columns that adapt to container width |

**Files:** `index.html` · `style.css` · `task2/index.html`

---

### 🌑 Box Shadow — Shadow Effects

> A centered card demonstrating `box-shadow` and `text-shadow` properties.

| Concept | Details |
|---------|---------|
| **Box Shadow** | Colored shadow with blur radius on a card |
| **Text Shadow** | Gray offset shadow on heading text |
| **Absolute Centering** | `position: absolute` + `transform: translate(-50%, -50%)` |

**Files:** `index.html`

---

### 🎨 Gradients — CSS Gradients & Animated Clock

> A deep dive into CSS gradients — from conic grids to text gradients to a **real-time animated clock**.

#### 🕐 Conic Gradient Clock (`clock.html`)
An animated clock built with three concentric circles, each representing **hours**, **minutes**, and **seconds**. The conic gradients rotate in real-time using JavaScript's `setInterval`.

```
┌──────────────────────┐
│    ╭─── Hours ───╮   │
│    │  ╭─ Min ─╮  │   │
│    │  │ ╭Sec╮ │  │   │
│    │  │ ╰───╯ │  │   │
│    │  ╰───────╯  │   │
│    ╰─────────────╯   │
└──────────────────────┘
```

#### 🌈 Text Gradient (`text-gradient.html`)
Applies a `linear-gradient` as a text fill using `background-clip: text` — a popular modern CSS technique.

#### 🔲 Gradient Grid (`gradients.html`)
A grid of boxes with `conic-gradient` backgrounds showcasing repeating visual patterns.

| Concept | Details |
|---------|---------|
| **Conic Gradients** | `conic-gradient()` for circular color sweeps |
| **Linear Gradients** | `linear-gradient()` for text fill effects |
| **DOM Manipulation** | JavaScript updates gradient rotation every 1ms |
| **CSS Grid** | 4-column responsive grid for gradient boxes |

**Files:** `clock.html` · `gradients.html` · `text-gradient.html`

---

### 📌 Positioning — CSS Position Types & Sticky Cards

> Two exercises exploring all CSS positioning modes and a creative sticky card gallery.

#### Position Types (`index.html`)
Demonstrates `static`, `relative`, `fixed`, `absolute`, and `sticky` positioning side by side.

#### 🏎️ Sticky Card Gallery (`task.html`)
A scrollable **Cars Collection** gallery where image cards stack on top of each other using `position: sticky` — creating a parallax-like card stacking effect.

| Concept | Details |
|---------|---------|
| **All Position Types** | static, relative, fixed, absolute, sticky |
| **Sticky Stacking** | Cards overlap while scrolling for a stacking effect |
| **CSS Variables** | Custom properties (`--rgb`) for text shadow colors |
| **Object-fit Cover** | Images fill cards without distortion |

**Files:** `index.html` · `task.html` · images

---

### 🧩 DOM — Document Object Model

> A styled page demonstrating DOM structure with Google Fonts integration, floating images, and text layout.

| Concept | Details |
|---------|---------|
| **Google Fonts** | Ubuntu font family imported via `@import` |
| **Float Layout** | Image floated left with text wrapping |
| **Dynamic Images** | `picsum.photos` for random placeholder images |
| **Custom Styling** | Dark theme with teal/cyan color palette |

**Files:** `index.html`

---

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="48" height="48" alt="HTML5" />
      <br><strong>HTML5</strong>
      <br><sub>Semantic Markup</sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="48" height="48" alt="CSS3" />
      <br><strong>CSS3</strong>
      <br><sub>Layouts & Styling</sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
      <br><strong>JavaScript</strong>
      <br><sub>DOM & Interactivity</sub>
    </td>
  </tr>
</table>

## 🧠 Key Concepts Covered

```
✅ Flexbox (centering, wrapping, alignment)
✅ CSS Grid (template areas, auto-fit, minmax)
✅ CSS Positioning (static, relative, absolute, fixed, sticky)
✅ Box Shadows & Text Shadows
✅ CSS Gradients (linear, conic)
✅ CSS Variables (custom properties)
✅ CSS Nesting (modern syntax)
✅ Responsive Design (@media queries)
✅ DOM Manipulation (querySelector, setInterval)
✅ Google Fonts Integration
```

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/kushal-soni01/full-stack-development.git

# Navigate into the project
cd full-stack-development

# Open any HTML file in your browser
# For example:
start gradients/clock.html        # Windows
open gradients/clock.html         # macOS
xdg-open gradients/clock.html     # Linux
```

> **No build tools or dependencies required** — just open the HTML files in any modern browser! 🌐

## 📝 License

This project is open source and available for learning purposes.

---

<div align="center">

**Made with ❤️ by [Kushal Soni](https://github.com/kushal-soni01)**

⭐ *Star this repo if you found it helpful!*

</div>
