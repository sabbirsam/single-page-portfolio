<div align="center">

# ⚡ Sabbir Ahmed Sam — Portfolio

### A single-file, zero-dependency developer portfolio with a terminal CV, 3D tilt cards, a sticky scroll story, and a full dark/light theme system.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-View%20Site-0F9B8E?style=for-the-badge&logo=vercel&logoColor=white)](https://sabbirsam.dev)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Vanilla JS](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![No Framework](https://img.shields.io/badge/Framework-None-2ea44f?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

<br/>

<!-- 🖼️ Swap this for an actual screenshot or a screen-recorded GIF of the site scrolling — that's the single biggest "wow" upgrade this README can get. -->
<img src="./assets/preview-dark.png" alt="Portfolio preview — dark mode" width="100%" />

<sub>Dark mode shown above · flips seamlessly to light mode with one click, no page reload</sub>

</div>

<br/>

## ✨ Why this exists

Most developer portfolios are a static resume with a nicer font. This one is built the way I build products — **fast, dependency-free, and designed to hold attention** the same way I want my plugins to hold up under real production traffic: no bloat, no framework tax, just deliberate engineering.

One `index.html`. No build step. No `node_modules`. Ship it anywhere.

<br/>

## 🎬 What makes it different

| | |
|---|---|
| 🖥️ **Terminal-style CV** | A `zsh`-styled terminal block types out `whoami`, `cat focus.txt`, and `ls wpazleen/` instead of a boring bullet list |
| 🧭 **Sticky scroll process story** | The left panel pins in place while the right column scrolls through 4 stages — powered by `IntersectionObserver`, not a library |
| 🃏 **Stacked-card journey timeline** | Career milestones cascade in as you scroll, each card sliding over the last — the effect a lot of portfolios fake with Framer Motion, done in ~40 lines of vanilla JS |
| 🎛️ **3D cursor-tilt cards** | Stack and product cards tilt toward your cursor in real 3D space with a light-follow glow |
| 🧲 **Magnetic buttons + custom cursor** | Primary CTAs subtly pull toward the pointer; a custom dot-and-ring cursor replaces the system one on desktop |
| 🌗 **Full theme engine** | Every color is a CSS custom property — dark/light mode swaps instantly and persists via `localStorage`, with zero flash on load |
| 🔍 **Filterable project grid** | Projects filter by `WPPOOL` / `WPAzleen` / `AI` with a single data attribute, no re-render logic |
| 🪟 **Product detail modals** | Click any showcase card for a full case-study modal — keyboard accessible, `Esc`-to-close, focus-safe |
| ♿ **Respects `prefers-reduced-motion`** | Every animation disables itself for users who ask for it — this isn't an afterthought |

<br/>

## 🧩 Sections

```
Hero            → animated role typewriter, parallax portrait, live stat counters
Terminal / CV   → zsh-style terminal + downloadable CV callout + logo marquee
About           → syntax-highlighted "about-me.php" card + career timeline
Process         → sticky 4-stage build process (Discover → Architect → Build → Ship)
Skills          → tabbed WordPress / Full-Stack / AI skill bars + tech chip cloud
Journey         → stacked-scroll career timeline (Research → Intern → QA → Lead)
Stack in 3D     → cursor-reactive tilt cards for each core competency
Projects        → filterable grid of 12 shipped WordPress plugins
Showcase        → click-to-expand case studies for flagship products
Research / AI   → RAG · Agents · MCP focus area + published CNN research paper
Contact         → validated contact form + socials, ready to wire into a real backend
```

<br/>

## 🛠️ Built with

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- **Zero runtime dependencies** — no React, no jQuery, no build tools
- **CSS custom properties** for a token-based design system (colors, radii, shadows, easing — one source of truth in `:root`)
- **`IntersectionObserver`** for scroll reveals, counters, skill bars, and the sticky story — no scroll-jank libraries
- **Google Fonts**: Space Grotesk (headings), Manrope (body), JetBrains Mono (terminal/code)
- Icons via [Skill Icons](https://skillicons.dev) and hand-drawn inline SVG

<br/>

## 🚀 Running it locally

No install, no build step — it's a single HTML file.

```bash
git clone https://github.com/sabbirsam/single-page-portfolio.git
cd single-page-portfolio

# just open it
open index.html

# or serve it (recommended, avoids file:// quirks)
npx serve .
```

<br/>

## 🎨 Making it your own

| Want to change... | Edit... |
|---|---|
| Colors / theme | `:root` and `[data-theme="light"]` custom properties at the top of the `<style>` block |
| Hero photo | Swap the `src` on `#heroPhoto` |
| Role titles (typewriter) | The `roles` array in the script |
| Projects | Duplicate a `.proj-card` block + add a matching entry to the `productData` object for its modal |
| Journey milestones | Duplicate a `.journey-item` block, bump `--i` |
| CV file | Replace `Sabbir-Ahmed-Sam-CV.pdf` and update the two `download` links |

<br/>

## 📬 Connect

<p align="left">
<a href="https://wpazleen.com/" target="_blank"><img src="https://img.shields.io/badge/WPAzleen-6c3bd8?style=for-the-badge&logo=wordpress&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/md-sabbir-ahmed-sam/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://twitter.com/itssabbirsam" target="_blank"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" /></a>
<a href="mailto:hello@wpazleen.com"><img src="https://img.shields.io/badge/Email-hello%40wpazleen.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<br/>

<div align="center">

**⭐ If this gave you an idea for your own portfolio, a star helps more than you'd think.**

</div>