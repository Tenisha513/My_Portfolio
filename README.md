# Tenisha Akhila Balla — Personal Portfolio Website

**Course:** 23CSE113 — User Interface Design | Amrita Vishwa Vidyapeetham  
**Live Site:** https://tenisha5132.github.io/My_Portfolio  
**GitHub Repo:** https://github.com/Tenisha5132/My_Portfolio

---

## Overview

A fully responsive personal portfolio website built using **pure HTML5 and CSS3** — no JavaScript frameworks, no external UI libraries. The site showcases my academic background, research interests, technical skills, and projects in AI, Data Science, and Cybersecurity.

The design follows a dark glassmorphism aesthetic with animated elements, gradient backgrounds, and a mobile-first responsive layout — built entirely through advanced CSS techniques.

---

## Live Preview

>>> Visit: **https://tenisha5132.github.io/My_Portfolio**

---

## Website Structure

The portfolio is a single-page application structured into the following sections:

| Section | Description |
|---|---|
| **Navigation** | Fixed navbar with 6 functional anchor links + CSS-only hamburger menu for mobile |
| **Hero** | Full-screen landing section with name, tagline, and CTA buttons |
| **Ticker** | Auto-scrolling skills marquee using CSS animation |
| **About Me** | Personal bio, stat cards, and sustainability focus |
| **Research Interests** | 6 glassmorphism cards covering AI/ML research areas |
| **Cybersecurity** | bi0s Red Team and ACM-SIGCyber activities |
| **Skills** | 6 skill cards with technology tags |
| **Projects** | 5 project cards with descriptions, images, and links |
| **Experience & Education** | Timeline layout from school to university |
| **Academic Projects** | Semester-by-semester project timeline |
| **Certifications & Clubs** | Two-column layout of achievements |
| **Contact** | Email, GitHub, and LinkedIn links |
| **Footer** | About Me, Contact Me, GitHub, LinkedIn links |

---

## Technologies Used

- **HTML5** — Semantic structure with proper use of `<nav>`, `<section>`, `<footer>`, headings, and accessibility attributes
- **CSS3** — All styling, layout, animations, and responsive design
- **Google Fonts** — Bebas Neue, Syne, Space Mono

---

## CSS Features Implemented

### Layout
- **CSS Grid** — Used for project cards, skill cards, research cards, about section, and extras section
- **Flexbox** — Used for navigation, buttons, tags, footer, and contact links

### Animations & Transitions
- `@keyframes slideup` — Hero text entrance animation
- `@keyframes badgepop` — Badge scale-in animation
- `@keyframes ticker` — Infinite horizontal scrolling marquee
- `@keyframes floatdot` — Floating particle background animation
- `@keyframes bgpulse` — Animated radial gradient background
- CSS `transition` on all hover effects (cards, buttons, nav links)

### Visual Design
- **Glassmorphism cards** — `backdrop-filter: blur()` with semi-transparent backgrounds
- **Gradient backgrounds** — `linear-gradient` and `radial-gradient` throughout
- **Box shadows** — Glow effects on card hover and buttons
- **CSS `::before` / `::after`** — Decorative grid overlay on hero, animated background layer
- **CSS Grid blueprint pattern** — Architectural grid on hero section using `background-image`

### Responsive Design (Media Queries)
- `@media (max-width: 900px)` — Stacks two-column grids to single column
- `@media (max-width: 768px)` — Shows hamburger menu, reduces section padding
- `@media (max-width: 480px)` — Full-width buttons, single-column all grids

### Navigation (CSS-only hamburger)
The mobile menu uses the **CSS checkbox trick** — no JavaScript required:
```css
#nav-toggle:checked ~ .nav-links { display: flex; }
```

### Hover Effects
- Cards lift with `translateY(-6px)` and emit a coloured glow
- Buttons shift diagonally with `translate(-3px, -3px)` and expand shadow
- Nav links reveal an underline via `width` transition on `::after`
- Timeline badges slide right on hover with `translateX(6px)`

### Smooth Scrolling
```css
html { scroll-behavior: smooth; }
```

---

## Project Showcase

The Projects section features 5 real projects with gradient image banners, technology tags, descriptions, results, and external links:

1. **G-DQN for UAV Swarms** — Multi-Agent RL for precision agriculture
2. **COVID-19 Dashboard** — ML forecasting with Scikit-learn (Colab link)
3. **Mindful Fridge** — Full-stack React + Supabase web app (GitHub link)
4. **CTF Mentor AI** — AI-powered cybersecurity learning platform (GitHub link)
5. **Retail Sales Forecasting** — Random Forest + Streamlit ML pipeline

---

## File Structure

```
My_Portfolio/
│
├── index.html       ← Main portfolio file (HTML + CSS in one file)
└── README.md        ← This file
```

---

| Criteria | Implementation |
|---|---|
| HTML Structure & Semantics | Semantic tags: `<nav>`, `<section>`, `<footer>`, headings hierarchy |
| Content Organisation & Accessibility | Logical section order, `aria-label` on hamburger button, alt-friendly emoji labels |
| CSS Styling & Layout | CSS Grid + Flexbox throughout, custom properties (CSS variables) |
| Visual Design & Navigation | Glassmorphism, gradients, glow effects, 6-link fixed navbar |
| Integration of HTML & CSS | Single-file, all CSS in `<style>` block, no external dependencies |
| Usability & Output | Responsive on all screen sizes, working links, smooth scroll |

---

## How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Tenisha5132/My_Portfolio.git
```
2. Open `index.html` in any browser.
---

## Author

**Tenisha Akhila Balla**  
B.Tech — Artificial Intelligence & Data Science  
Amrita Vishwa Vidyapeetam, Amritapuri  
📍 Visakhapatnam, Andhra Pradesh
