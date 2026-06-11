# Atharv Khaire — Portfolio Website

A personal portfolio website for Atharv Ramchandra Khaire, an aspiring Cloud & Java Developer pursuing B.Tech in Computer Science Engineering (Honours in Cloud Computing) at JSPM University, Pune.

---

## Live Preview

Open `atharv_portfolio.html` directly in any modern browser — no build step or server required.

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, transitions
- **Vanilla JavaScript** — IntersectionObserver for scroll-reveal animations
- **Google Fonts** — Space Grotesk (display/body) + JetBrains Mono (code/labels)

---

## Sections

| Section | Description |
|---|---|
| Hero | Name, tagline, key stats, CTA buttons |
| Target Roles | Highlighted internship roles being sought |
| Skills | Cloud & DevOps, Languages, Web, Database, Core CS |
| Experience | Timeline of 3 internships |
| Projects | ATM Simulation, Responsive Website |
| Certifications | 6 certifications from NPTEL, EduSkills, CAD-IT DESK |
| Education | B.Tech, Diploma, HSC, SSC |
| Contact | Email, phone, LinkedIn, GitHub |

---

## Project Structure

```
portfolio/
├── atharv_portfolio.html   # Single-file portfolio (HTML + CSS + JS)
└── README.md               # This file
```

---

## Features

- **Single file** — everything bundled in one `.html` file
- **Responsive** — works on mobile, tablet, and desktop
- **Scroll animations** — elements fade in as you scroll using `IntersectionObserver`
- **Reduced motion** — respects `prefers-reduced-motion` for accessibility
- **No dependencies** — no frameworks, no npm, no build tools

---

## Customisation

All design tokens are CSS variables at the top of the `<style>` block:

```css
:root {
  --bg:       #0B0F1A;   /* page background */
  --surface:  #111827;   /* card background */
  --accent:   #00C2FF;   /* primary highlight colour */
  --accent2:  #7B5EA7;   /* secondary highlight colour */
  --text:     #E8EEF4;   /* body text */
  --muted:    #6B7A8D;   /* secondary text */
}
```

To update content, edit the relevant HTML section directly — each section is clearly commented.

---

## Contact

**Atharv Ramchandra Khaire**  
Shikrapur, Pune, Maharashtra  
📧 atharvkhaire18@gmail.com  
📞 +91 98907 42664  
🔗 [linkedin.com/in/atharv-khaire-0b2a83314](https://linkedin.com/in/atharv-khaire-0b2a83314)  
💻 [github.com/atharvkhaire18](https://github.com/atharvkhaire18)
