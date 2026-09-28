# Personal Portfolio — omar-argenes.netlify.app

Bilingual (English / Spanish) portfolio built by hand with **HTML, CSS and vanilla JavaScript** — no framework and no build step — with a WebGL background, a 3D globe on canvas and animated SVG diagrams.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

**Live:** [omar-argenes.netlify.app](https://omar-argenes.netlify.app/)

> The source repository is private. This repository presents the design and the engineering behind the site.

![Hero](assets/hero.webp)

---

## Highlights

| Feature | How it works |
|---|---|
| **WebGL aurora background** | Custom fragment shader with domain-warped noise. A soft light follows the pointer; on touch devices it drifts on its own. Rendered at half resolution and paused when the tab is hidden. |
| **3D globe** | Canvas 2D projection of a point sphere with a great-circle arc between Cochabamba and Hamburg and a pulse travelling along it. Reacts to the pointer and stops when off-screen. |
| **Live world clock** | Current time in Cochabamba, Hamburg and New York with a day/night indicator (`Intl.DateTimeFormat`). |
| **Animated IT network** | SVG diagram — router, switch, server, workstations, Wi-Fi and CCTV — with data packets moving along the links (SMIL) and blinking status LEDs (CSS). |
| **Bilingual without duplication** | English text lives in the HTML and is captured at load; only the Spanish dictionary is kept in JavaScript. A dev check warns about missing translations. |
| **Verifiable content** | Experience links to real merged pull requests and project showcases on GitHub. |

## Screenshots

| Experience | IT infrastructure |
|---|---|
| ![Experience](assets/experience.webp) | ![IT infrastructure](assets/it.webp) |

| Research (DFI) | Contact |
|---|---|
| ![Research](assets/research.webp) | ![Contact](assets/contact.webp) |

### Mobile

<p>
  <img src="assets/mobile-hero.webp" width="240" alt="Mobile — hero" />
  <img src="assets/mobile-experience.webp" width="240" alt="Mobile — experience" />
  <img src="assets/mobile-it.webp" width="240" alt="Mobile — IT section" />
</p>

## Quality

- **Responsive** from 360 px phones to wide desktops, checked with headless Chrome at several widths.
- **Accessibility:** skip link, visible focus styles, semantic sections, `aria` labels on icon links, and `prefers-reduced-motion` support (CSS, canvas, WebGL and SVG animations stop).
- **Performance:** WebP images with explicit sizes, lazy-loaded screenshots, animations paused when not visible, no framework runtime.
- **SEO & sharing:** Open Graph image, canonical URL and `Person` structured data (JSON-LD).

## Stack

HTML · CSS (custom properties, grid, `@property`) · JavaScript (ES2020+) · WebGL · Canvas 2D · SVG / SMIL · Netlify

---

**Author:** [Omar Argenes Quispe](https://github.com/OmarArgenes) · [Portfolio](https://omar-argenes.netlify.app/)
