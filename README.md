# FlipStuck — Master Microsoft Excel (Beginner to Advanced)

[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen.svg?style=flat-square)](https://sandbyte-flipstuck-task-two.vercel.app)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Modern_Vanilla-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-WAAPI-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)](https://sandbyte-flipstuck-task-two.vercel.app)

A high-converting, accessible, and responsive course landing page for **FlipStuck's flagship Microsoft Excel Masterclass**, designed with modern web architecture and visual aesthetics.

🔗 **Live Production Demo**: [https://sandbyte-flipstuck-task-two.vercel.app](https://sandbyte-flipstuck-task-two.vercel.app)

---

## 🌟 Key Features

* **High-Impact Hero & Pricing**: Conversion-focused value proposition, social proof trust badges, one-time enrollment pricing (₹49,301), and primary call-to-actions.
* **Interactive Video Preview Modal**: Accessible modal overlay (`role="dialog"`, `aria-modal="true"`) with keyboard trap (`Escape` key close) and focus restoration.
* **Infinite Looping Marquees**:
  * **Partner Companies Ticker**: Seamless infinite CSS ticker showcasing top hiring partners (Google, Microsoft, Amazon, Adobe, Udemy, Notion).
  * **Verified Certificates & Student Showcase**: Continuous dual-track horizontal marquee highlighting student completion certificates and testimonials.
* **Dynamic 8-Module Curriculum**: Smooth accordion interactions powered by the native **Web Animations API (WAAPI)** with exclusive single-item expansion dynamics.
* **Instructor Spotlight**: Amit Kumar's profile with verified student review cards and rating metrics.
* **Comparison Matrix Table**: Why Learners Trust FlipStuck vs. YouTube vs. Competitor Institutes feature breakdown.
* **FAQ Accordion**: 6 collapsible frequently asked questions addressing common learner concerns.
* **Designed for Real People Banner**: Pre-footer showcase featuring 3D holographic human visualization and Learn/Grow/Succeed value pillars.
* **Comprehensive Footer & Legal**: Category navigation, social channels, copyright bar, and contact details.
* **Mobile-First Responsiveness**: Pure CSS mobile drawer navigation with zero layout shift across 1024px, 768px, 640px, and 480px viewports.
* **Floating Back-to-Top**: Smooth scroll-to-top interaction with scroll-aware navbar backdrop blur.

---

## 🛠️ Tech Stack & Architecture

| Layer | Technology | Details |
|---|---|---|
| **Structure** | Semantic HTML5 | Accessible landmark roles, skip-to-content links, Schema.org JSON-LD |
| **Styling** | Vanilla Modern CSS3 | CSS Custom Properties (Design Tokens), Flexbox, CSS Grid, clamp() fluid typography, backdrop filters |
| **Interactions** | Vanilla JavaScript | Web Animations API (`element.animate()`), IntersectionObserver, passive scroll handlers |
| **SEO & Social** | OpenGraph & Twitter Cards | Rich metadata preview cards and PWA Web App Manifest (`site.webmanifest`) |
| **Performance** | Native Browser APIs | `loading="lazy"`, `fetchpriority="high"`, `decoding="async"`, immutable asset cache headers |

---

## 📁 Repository Structure

```text
.
├── Assets-2/                   # Optimized images, partner logos, certificates, icons
├── favicon.ico                 # Standard multi-resolution favicon
├── favicon.png                 # Apple touch icon & PWA manifest icon
├── index.html                  # Semantic course landing page markup
├── style.css                   # Complete design system tokens, components, and media queries
├── site.webmanifest            # PWA web manifest
├── vercel.json                 # Caching and production deployment configuration
└── README.md                   # Project documentation
```

---

## 🚀 Local Development

To run the project locally without any dependencies:

```bash
# Clone the repository
git clone https://github.com/xjaskiratx/SbFsTaskTwo.git
cd SbFsTaskTwo

# Open in browser or run a simple local HTTP server
python3 -m http.server 3000
# or
npx serve .
```

Navigate to `http://localhost:3000` to preview.

---

## 📈 25-Commit Development Timeline

| Batch | Day | Commits | Focus Areas |
|---|---|---|---|
| **Batch 1** | Oct 2, 2026 | `01–05` | Repository setup, design tokens, asset extraction, favicons, semantic header |
| **Batch 2** | Oct 3, 2026 | `06–10` | Hero section, preview monitor, partner ticker, 8-module curriculum structure |
| **Batch 3** | Oct 3, 2026 | `11–15` | Instructor profile, verified proof showcase, career support, comparison table, FAQ |
| **Batch 4** | Oct 4, 2026 | `16–20` | Real people banner, site footer, video demo modal, proof marquee upgrade, responsive media queries |
| **Batch 5** | Oct 5, 2026 | `21–25` | Keyboard a11y & skip links, back-to-top interaction, SEO schema & OpenGraph, Core Web Vitals perf, documentation |

---

## 📄 License

This project was built for the FlipStuck Frontend Development Task. All rights reserved.
