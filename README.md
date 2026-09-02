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

This repository is a collection of **practical exercises and mini-projects** built while learning full-stack web development. Each folder focuses on a specific CSS/HTML/JS concept, progressing from fundamentals to more advanced techniques like CSS Grid layouts, conic-gradient clocks, flexbox dashboards, CSS selectors, typography, and dashboard UIs.

## 🗂️ Project Structure

```
Full-stack/
│
├── task1-2/          🔐 Login Card & Navbar
├── task3/            🛒 Product Cards (Flexbox)
├── task4/            📊 Admin Dashboard (CSS Grid)
├── flex-box/         📐 Flexbox Deep Dive & Dashboard
├── bento/            🍱 Bento Grid Layouts
├── box-shadow/       🌑 Box Shadow & Text Shadow
├── gradients/        🎨 CSS Gradients & Animated Clock
├── positioning/      📌 CSS Positioning & Sticky Cards
├── selectors/        🎯 CSS Selectors & Pseudo-classes
├── outline_float/    📰 Outline, Float & Newspaper Layout
├── typography/       🔤 Google Fonts & Typography
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

### 📐 Flex-box — Flexbox Deep Dive & Dashboard

> Three exercises exploring Flexbox fundamentals, interactive login cards, flex grow/shrink/basis properties, and a full Flexbox-powered admin dashboard.

#### 🔐 Login Card (`index.html`)
A centered login card using `display: flex` with column direction and smooth transition hover effects on the container and inputs.

#### 🧪 Flex Playground (`play.html`)
Interactive Flexbox sandbox demonstrating `flex-grow`, `flex-shrink`, and `flex-basis` properties side by side on three colored boxes.

#### 📊 Flexbox Admin Dashboard (`task.html`)
A full admin dashboard rebuilt with **Flexbox** — dark sidebar with Font Awesome icons, blue header with user profile, stat cards for Users / Products / Orders / Revenue, and a styled data table with alternating row colors.

| Concept | Details |
|---------|---------|
| **Flex Direction** | Column sidebar + row main content layout |
| **flex-grow / shrink / basis** | Dynamic box sizing with shorthand `flex` property |
| **Font Awesome Icons** | CDN-loaded icons in sidebar and stat cards |
| **CSS Nesting** | Deeply nested modern CSS for scoped component styles |
| **Hover Transitions** | Smooth nav-link hover background effects |

**Files:** `index.html` · `play.html` · `task.html`

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

### 🎯 Selectors — CSS Selectors & Pseudo-classes

> Two exercises covering CSS combinators, state pseudo-classes, and form validation pseudo-classes.

#### CSS Combinators (`index.html`)
Hands-on demo of descendant (` `), child (`>`), adjacent sibling (`+`), and general sibling (`~`) selectors alongside `:hover`, `:focus`, and `:active` interaction states.

#### 📋 Form Pseudo-classes (`form-psedo.html`)
A form where fields visually respond to `:required`, `:optional`, `:valid`, `:invalid`, `:in-range`, and `:out-of-range` states. Also demonstrates `:nth-child()` and `:not()` for pattern-based list styling.

| Concept | Details |
|---------|---------|
| **Combinator Selectors** | Descendant, child, adjacent & general sibling |
| **State Pseudo-classes** | `:hover`, `:focus`, `:active` on interactive elements |
| **Form Validation** | `:required`, `:optional`, `:valid`, `:invalid` |
| **Range Validation** | `:in-range`, `:out-of-range` for number inputs |
| **Structural** | `:nth-child()` and `:not()` for pattern-based styling |

**Files:** `index.html` · `form-psedo.html`

---

### 📰 Outline & Float — Float Layout & Newspaper Design

> Two exercises practicing CSS `outline` vs `border` and `float`-based layouts including a classic newspaper-style page.

#### Float with Outline (`index.html`)
Full-viewport card outlined with `outline: 10px solid blue` — demonstrating how `outline` sits outside the box model. An image is floated right with text wrapping around it.

#### 🗞️ Newspaper Layout (`newspaper.html`)
Classic newspaper-style header layout with a floated image inside an article section — illustrating float-based editorial web design.

| Concept | Details |
|---------|---------|
| **CSS Outline** | `outline` vs `border` — sits outside the box model |
| **Float Right** | Image floated right with automatic text wrap-around |
| **Newspaper Layout** | Header + article body using float-based composition |

**Files:** `index.html` · `newspaper.html`

---

### 🔤 Typography — Google Fonts & Font Properties

> An in-depth exploration of Google Fonts and CSS typography properties across five font families.

Five test divs each using a different Google Font or system font stack — **Ubuntu**, **Lucida Sans**, **Black Ops One**, **Dancing Script**, and **Caveat** — tuned with `font-size-adjust` and `font-stretch` to compare visual weight, x-height, and rhythm.

| Concept | Details |
|---------|---------|
| **Google Fonts** | `@import` of Ubuntu, Black Ops One, Dancing Script, Caveat |
| **font-size-adjust** | Preserves x-height ratio when fallback fonts kick in |
| **font-stretch** | Expanded/condensed glyph variants |
| **Font Stacks** | Graceful fallback chains for each font family |
| **Form Styling** | Input fields with border-radius and custom font rendering |

**Files:** `index.html`

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
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="48" height="48" alt="Google Fonts" />
      <br><strong>Google Fonts</strong>
      <br><sub>Typography</sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fontawesome/fontawesome-original.svg" width="48" height="48" alt="Font Awesome" />
      <br><strong>Font Awesome</strong>
      <br><sub>Icon Library</sub>
    </td>
  </tr>
</table>

## 🧠 Key Concepts Covered

```
✅ Flexbox (centering, wrapping, grow/shrink/basis, column layouts)
✅ CSS Grid (template areas, auto-fit, minmax)
✅ CSS Positioning (static, relative, absolute, fixed, sticky)
✅ Box Shadows & Text Shadows
✅ CSS Outlines (vs border — outside the box model)
✅ CSS Float (image wrap, newspaper-style layouts)
✅ CSS Gradients (linear, conic)
✅ CSS Variables (custom properties)
✅ CSS Nesting (modern syntax)
✅ CSS Selectors (combinators, pseudo-classes, :nth-child, :not)
✅ Form Validation Pseudo-classes (:required, :valid, :in-range…)
✅ Responsive Design (@media queries)
✅ Typography (font-size-adjust, font-stretch, font stacks)
✅ Google Fonts Integration
✅ Font Awesome Icons (CDN)
✅ DOM Manipulation (querySelector, setInterval)
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
