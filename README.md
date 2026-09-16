<div align="center">

# 🛡️ Muhammad Umair — Cyber-Executive Portfolio

**A dark-themed personal portfolio engineered with a cybersecurity-first aesthetic — pure HTML5, CSS3 (custom design system), and vanilla JavaScript.**

[![Live Demo](https://img.shields.io/badge/Live_Portfolio-umairs759.github.io-D6FF4A?style=for-the-badge&logo=githubpages&logoColor=08080A)](https://umairs759.github.io/Muhammad-Umair-Portfolio/)
[![Tech Stack](https://img.shields.io/badge/Stack-HTML5_·_CSS3_·_JavaScript-08080A?style=for-the-badge&logo=javascript&logoColor=D6FF4A)](#-built-with)
[![License](https://img.shields.io/badge/License-MIT-4ADE80?style=for-the-badge)](#-license)
[![Status](https://img.shields.io/badge/Status-Actively_Maintained-4361EE?style=for-the-badge)](#)

[Live Site](https://umairs759.github.io/Muhammad-Umair-Portfolio/) · [Report Bug](https://github.com/umairs759/Muhammad-Umair-Portfolio/issues) · [Request Feature](https://github.com/umairs759/Muhammad-Umair-Portfolio/issues)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Live Preview](#-live-preview)
- [Key Features](#-key-features)
- [Built With](#-built-with)
- [Featured Projects](#-featured-projects)
- [Credentials & Milestones](#-credentials--milestones)
- [Project Structure](#-project-structure)
- [Local Setup](#-local-setup)
- [Customisation Guide](#-customisation-guide)
- [Performance & Accessibility](#-performance--accessibility)
- [Contact & Connect](#-contact--connect)
- [License](#-license)

---

## 📌 About

This portfolio was built from scratch — no frameworks, no build tools, no dependencies beyond a Google Fonts import and Font Awesome icons. It showcases the work of **Muhammad Umair**, a Cyber Security Specialist, Python Developer, and AI Automation Engineer based in Lahore, Pakistan.

The design language is intentionally sharp: a near-black canvas, a single acid-lime accent, editorial serif display type paired with monospaced technical labels, and subtle motion that respects `prefers-reduced-motion`. Everything is designed to feel like a security console that happens to be a portfolio.

---

## 🌐 Live Preview

**👉 [https://umairs759.github.io/Muhammad-Umair-Portfolio/](https://umairs759.github.io/Muhammad-Umair-Portfolio/)**

Deployed automatically via GitHub Pages from the `main` branch.

---

## 🌟 Key Features

### 🎨 Design & UI
- **Cyber-Executive Design System** — full CSS custom-property token system for colours, spacing, typography, easing curves, and shadow scales.
- **Fluid Typography** — every heading and body size uses `clamp()` for seamless scaling from 320px phones to ultra-wide displays.
- **Dark-first Aesthetic** — layered greys, acid-lime accent, film-grain texture overlay, and blurred radial glows.
- **Print Stylesheet** — the portfolio converts to a clean, readable, ink-friendly layout when printed or saved as PDF.

### ⚡ Interactive Dynamic UI
- **Custom Cursor** — dual-layer dot + ring cursor with magnetic hover states (auto-disabled on touch devices).
- **Scroll Progress Bar** — thin acid-lime indicator at the top of the viewport.
- **IntersectionObserver Reveals** — elements fade and rise into view with staggered timing based on sibling order.
- **Animated Project Visuals** — chat bubbles, equity-curve SVG drawing, pipeline flow, bar growth, and a rotating 3D cube, all CSS/SVG-driven.
- **Live Lahore Clock** — real-time `Asia/Karachi` timezone display in the navigation bar.
- **Count-Up Statistics** — animated metrics triggered on scroll into viewport.
- **1-Click Email Copy** — clipboard API with a graceful fallback for older browsers and a feedback toast.
- **Working Contact Form** — posts via FormSubmit AJAX directly to the owner's inbox, no backend required.

### 🔍 SEO & Accessibility
- **Semantic HTML5 landmarks** — `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- **Schema.org Person JSON-LD** — structured data for search engines.
- **OpenGraph + Twitter Card** meta tags for rich social sharing.
- **ARIA attributes** on interactive controls (`aria-expanded`, `aria-controls`, `aria-label`, `aria-live`).
- **Skip-to-content link** for keyboard and screen-reader users.
- **`prefers-reduced-motion`** fully respected — all animations collapse to instant states.

---

## 🛠️ Built With

| Category | Technology |
| --- | --- |
| **Core** | HTML5, CSS3, Vanilla ES6+ JavaScript |
| **Design System** | CSS Custom Properties (Variables), CSS Grid, Flexbox |
| **Typography** | [Fraunces](https://fonts.google.com/specimen/Fraunces), [Inter Tight](https://fonts.google.com/specimen/Inter+Tight), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) |
| **Form Backend** | [FormSubmit.co](https://formsubmit.co/) (AJAX endpoint, no signup) |
| **Hosting** | GitHub Pages |
| **Tools** | Git, VS Code, Chrome DevTools |

**Zero build step. Zero npm dependencies. Zero frameworks.** Just open `index.html` and it runs.

---

## 🚀 Featured Projects

The portfolio highlights seven real, working projects spanning AI, security, retail, 3D web, finance, data, and growth.

### 🤖 LocalBiz AI WhatsApp Agent
A 24/7 AI WhatsApp receptionist for local businesses — a free SaaS alternative using the Meta API with **Groq Llama 3.3 → Gemini 2.0 failover**. Handles customer queries, qualifies leads, and routes orders. Docker-ready for one-command deployment.
`Python` · `FastAPI` · `Docker` · `Groq` · `Gemini` · `Meta WhatsApp Cloud API`

### 📊 BrandPulse AI Agent
A state-of-the-art AI agent that bridges local businesses and data-driven intelligence. Automates reputation management, sentiment tracking, and customer engagement — turning scattered feedback into actionable insight.
`Python` · `AI Agent` · `Sentiment Analysis` · `Reputation Management`

### 🧾 RetailFlow-POS
A lightweight, offline-first retail management and POS console built with pure Vanilla JS. Instant billing, Khata (credit book), WhatsApp digital receipts, and inventory tracking — runs entirely in the browser with no backend.
`Vanilla JavaScript` · `HTML5` · `LocalStorage` · `Offline-First`

### 🍗 Labaik Broast
An interactive 3D restaurant web application with custom WebGL scenes, smooth camera work, and a full menu experience. Engineered to feel premium on desktop and mobile alike.
`Three.js` · `JavaScript` · `WebGL`

### 📈 Algorithmic Trading Bots
Automated strategies and Expert Advisors (EAs) for MetaTrader 5 and TradingView, driven by Python automation. Every strategy ships with hard-coded risk limits, position sizing rules, and a kill-switch.
`MetaTrader 5` · `MQL5` · `TradingView` · `Python` · `Risk Management`

### 📋 Tally.so Lead Pipelines
Scalable cloud form systems deployed for local brands (including Pizza Heights) — capturing leads, scoring intent, and pushing structured data into dashboards with sentiment tracking.
`Tally.so` · `Cloud Forms` · `Sentiment Analysis` · `Analytics`

### 🚀 SEO & Digital Growth Engine
Rebuilt content and metadata architecture for a sports media channel — restructuring information hierarchy, fixing crawl waste, and rewriting titles around actual search intent. Result: **230K+ organic views in a single week.**
`SEO` · `Metadata Optimization` · `Content Strategy` · `Analytics`

---

## 🏆 Credentials & Milestones

| Year | Achievement |
| --- | --- |
| **2026** | 🥈 **Top 20% Global Rank** — International Research Olympiad |
| **2026** | ☁️ **Grade 2A Placement** — Alibaba Cloud AI Hackathon Pakistan (Bano Qabil) |
| **2026** | 🔐 **Microsoft Applied Skills** — Cloud Security & Monitoring Tasks |
| **2026** | 🛡️ **Google Foundations of Cybersecurity** — Coursera |
| **2026** | 🏢 **Deloitte Cybersecurity Job Simulation** — Enterprise Incident Response |
| **2026** | 🎓 **Microsoft Learn Student Ambassador** — Community Influencer Track (`studentamb_625350`) |
| **2026** | 💻 **Major League Hacking (MLH) Fellowship** — Applicant |
| **2026** | 🗄️ **Microsoft Learn** — SQL Database Objects & Data Security |
| **2025** | 📈 **Digital Marketing & SEO Certification** — JDC Free IT City |

---

## 📂 Project Structure

Muhammad-Umair-Portfolio/
│
├── index.html # Single-file portfolio (HTML + CSS + JS inline)
├── Portfliopic.png # Hero portrait image
├── README.md # This file
└── LICENSE # MIT License


Everything is contained within `index.html` — styles and scripts are inlined for zero-latency first paint and simple deployment.

---

## 💻 Local Setup

### Option 1 — Direct open (fastest)

```bash
git clone https://github.com/umairs759/Muhammad-Umair-Portfolio.git
cd Muhammad-Umair-Portfolio

Then double-click index.html, or drag it into any modern browser.
Option 2 — Local live server (recommended for development)

###Using Python 3:

python3 -m http.server 8000

Then open http://localhost:8000.

###Using VS Code:
Install the Live Server extension, right-click index.html, and choose "Open with Live Server".

Using Node.js:

npx serve .

##🎨 Customisation Guide

Want to adapt this portfolio for yourself? Everything you need is in index.html.
What to change	Where to look
Colour palette	:root block at the top of the <style> tag — edit --acid, --ink, --paper
Typography	--f-display, --f-sans, --f-mono variables
Personal info (name, role, bio)	Hero section and <section id="about">
Projects	<section id="work"> — each <article class="project"> block
Achievements	<section id="recognition"> — each .tl-item block
Email address	Search for umairghaffar759@gmail.com (appears in form action, mailto links, and JSON-LD)
Social links	Hero CTA buttons and .c-socials block in the contact section
Hero portrait	Replace Portfliopic.png with your own image (keep the same filename, or update the src)
SEO metadata	<head> — <title>, <meta name="description">, OpenGraph, and Twitter tags


##⚡ Performance & Accessibility

    No external JS libraries — total script payload is under 12 KB uncompressed.

    No render-blocking resources — fonts load with display=swap; icons are inline SVG.

    Optimised assets — the hero image uses loading="eager" and decoding="async".

    Lighthouse-friendly — semantic markup, adequate colour contrast, and no layout shift.

    Accessible by default — keyboard navigable, screen-reader tested, and compliant with prefers-reduced-motion.

##📬 Contact & Connect
<div align="center">

###Muhammad Umair — Cyber Security Specialist · Python Developer · AI Automation Engineer

📍 Lahore, Pakistan

https://img.shields.io/badge/Email-umairghaffar759@gmail.com-D6FF4A?style=for-the-badge&logo=gmail&logoColor=08080A
https://img.shields.io/badge/GitHub-@umairs759-08080A?style=for-the-badge&logo=github&logoColor=D6FF4A
https://img.shields.io/badge/LinkedIn-umairghaffar759-4361EE?style=for-the-badge&logo=linkedin&logoColor=white
</div>
##📄 License

This project is open-source and available under the MIT License. See the LICENSE file for details.

You are free to use this portfolio as inspiration or a starting template — a credit or star on the repository is always appreciated but never required.
<div align="center">

###⭐ If you found this portfolio useful or inspiring, consider giving it a star — it helps others discover it.

Made with an obsession for detail in Lahore, Pakistan.
</div> ```
