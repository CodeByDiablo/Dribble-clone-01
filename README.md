# 🎨 Dribbble Clone 01

A clean and responsive **Dribbble Landing Page Clone** built using only:

- HTML5
- CSS3

This project recreates the modern Dribbble UI while focusing on:

- Clean Visual Hierarchy
- Semantic HTML Structure
- Reusable Components
- Responsive Layouts
- CSS Grid & Flexbox
- Smooth Hover Animations
- Professional Frontend Architecture

---

# 🚀 Live Demo

### Deployment (GitHub Pages)
https://codebydiablo.github.io/Dribble-clone-01/

---

# 📌 Features

✅ Fully Responsive Design  
✅ Pure HTML & CSS  
✅ No Tailwind CSS  
✅ Semantic DOM Structure  
✅ Smooth Card Hover Effects  
✅ Infinite Brand Slider  
✅ Modern UI Layout  
✅ Responsive Grid System  
✅ Reusable Card Components  
✅ Professional File Structure  

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling |
| Flexbox | Layout Alignment |
| CSS Grid | Cards Layout |
| Remix Icons | Icons |
| Google Fonts | Typography |
| GitHub Pages | Deployment |

---

 #🌳 DOM Structure

 ```
html
└── body
    ├── header.navbar
    │
    ├── main
    │   ├── section.hero-section
    │   ├── section.search-section
    │   ├── section.tags-section
    │   ├── section.filter-section
    │   ├── section.cards-section
    │   │   ├── article.card
    │   │   ├── article.card
    │   │   ├── article.card
    │   │   └── ...
    │   │
    │   ├── section.continue-section
    │   └── section.brands-slider
    │
    └── footer.footer
```

---

# 🎯 Frontend Concepts Used
This project helped practice several important frontend concepts:
 • Semantic HTML
 • DOM Structure
 • Component Thinking
 • Visual Hierarchy
 • CSS Architecture
 • Responsive Design
 • Hover Interactions
 • Animation Systems
 • Layout Design
 • UI/UX Principles

---

# 🧠 How I Created This Webpage

This project was built by first analyzing the original Dribbble landing page design and then recreating it using semantic HTML and pure CSS.

The main goal was not just cloning the UI visually, but also creating a clean frontend architecture.

---

## Step 1 - Creating Semantic Structure

The webpage was divided into logical sections:

- Navbar
- Hero Section
- Search Section
- Tags Section
- Filter Section
- Cards Grid
- Brand Slider
- Footer

Instead of using random divs, semantic tags were used like:

```html
<header>
<main>
<section>
<article>
<footer>
```

This improves:
 • readability
 • accessibility
 • maintainability
 • SEO

## Step 2 - Building Layout Systems

Flexbox was used for:
 • Navbar
 • Search bar
 • Footer
 • Filter section
 • Card info alignment

CSS Grid was used for:
 • Cards Layout
 ```
.cards-section{
    display:grid;
    grid-template-columns:repeat(4,1fr);
}
```

## Step 3 - Creating Reusable Card Components
Instead of writing separate styles for every card, a reusable .card component system was created.
```
.card
    ├── .card-image
    ├── .card-overlay
    ├── .card-info
    ├── .profile-info
    └── .card-stats
```

## Step 4 - Adding Hover Animations
Smooth hover animations were added using:
```
transition:0.7s cubic-bezier(0.19,1,0.22,1);
```

## Step 5 - Infinite Brand Slider
A continuous horizontal brand slider was created using:
 • overflow:hidden
 • white-space:nowrap
 • CSS Keyframes Animation

## Step 6 - Responsive Design
Media queries were added for:
 • Tablets
 • Mobile devices
 • Smaller screens
The cards automatically change from:
```
4 Columns → 3 Columns → 2 Columns → 1 Column
```
---
