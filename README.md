# Thermal Physics Games — Standalone Editions

Self-contained HTML files for deployment on GitHub Pages, WordPress, or any static hosting platform. Each file includes all CSS, JavaScript, and game data inline — no external dependencies other than Google Fonts CDN.

## Games

| Game | File | Description |
|------|------|-------------|
| Thermal Warmup | `thermal-warmup.html` | Calculate heating times using specific heat capacity, mass, and power. Covers simple heating, phase changes, and multi-stage thermal processes. |
| Thermal Equilibrium | `thermal-equilibrium.html` | Explore heat exchange between metals and water. Includes calorimetry, data centre liquid cooling, and two-phase immersion cooling. |
| Thermal Brew | `thermal-brew.html` | Boil water in real-world kettles, mix tea with milk, and add ice cubes. Accounts for thermal mass, multi-body equilibrium, and latent heat. |

## Features

- 3 levels per game with increasing complexity
- Randomised questions for replayability
- Animated heating/cooling curve graphs (HTML5 Canvas)
- Real-time feedback with contextual hints
- Confetti and point animations on correct answers
- Reference tables for thermal properties
- Fully responsive design (desktop, tablet, mobile)

## Deployment

### GitHub Pages

1. Push these files to a public GitHub repository
2. Enable GitHub Pages in repository **Settings > Pages**
3. Access via `https://<username>.github.io/<repo>/<filename>.html`

### WordPress (via link)

Add a **Custom HTML** block in your WordPress post:

```html
<a href="https://<username>.github.io/<repo>/thermal-warmup.html"
   target="_blank">Play Thermal Warmup</a>
```

### Direct hosting

Upload the HTML files to any web server or static hosting service (Netlify, Vercel, Cloudflare Pages, etc.). No build step or server-side processing required.

## Technology

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Graphics**: HTML5 Canvas API for animated graphs
- **Fonts**: Google Fonts (Orbitron, Inter, JetBrains Mono)
- **Icons**: Google Material Symbols Outlined
- **Design**: Dark sci-fi glassmorphism theme

## Licence and Copyright

Copyright &copy; 2026 Nanyang Technological University (NTU), Singapore. All rights reserved.

These materials are the intellectual property of Nanyang Technological University. Unauthorised reproduction, distribution, display, or modification of any part of these materials, in any form or by any means, is strictly prohibited without prior written permission from NTU.

For permissions or licensing enquiries, please contact Nanyang Technological University.

---

*Developed at Nanyang Technological University, Singapore.*
