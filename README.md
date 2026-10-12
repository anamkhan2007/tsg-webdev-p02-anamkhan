# FORGE Strength Studio 💪

**A bold, responsive landing page for a modern strength-training studio.**

[![Live Website](https://img.shields.io/badge/Live%20Website-Visit%20Site-ff4b24?style=for-the-badge)](https://forge-strength-studio.netlify.app/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Source%20Code-181717?style=for-the-badge&logo=github)](https://github.com/anamkhan2007/tsg-webdev-p02-anamkhan)

## 🔗 Project Links

- **Live website:** https://forge-strength-studio.netlify.app/
- **GitHub repository:** https://github.com/anamkhan2007/tsg-webdev-p02-anamkhan

## 📸 Website Preview

### Desktop Homepage

![FORGE Strength Studio desktop homepage](screenshots/homepage-desktop.png)

## ✨ Features

- Responsive business landing page for desktop, tablet, and mobile layouts
- Navigation with section links and clear calls to action
- Hero section with bold brand messaging and trial-booking actions
- Program, method, pricing, member, FAQ, and contact content sections
- Interactive page elements powered by JavaScript
- Dark visual style with vivid orange accents and strong typography
- Built CSS assets included for static deployment

## 🧰 Tech Stack

- HTML5
- CSS3 / Tailwind CSS
- JavaScript
- Google Fonts/local WOFF2 font assets
- Netlify for deployment

## 🚀 Lighthouse Audit

The live website was audited in Chrome DevTools using Lighthouse 13.4.1 on **October 13, 2026**. The supplied report was captured in desktop emulation during an initial page load; results can vary between runs and devices.

| Category | Score |
|---|---:|
| Performance | **99/100** |
| Accessibility | **100/100** |
| Best Practices | **100/100** |
| SEO | **100/100** |

### Key Performance Metrics

| Metric | Result |
|---|---:|
| First Contentful Paint (FCP) | 0.4 s |
| Largest Contentful Paint (LCP) | 0.9 s |
| Total Blocking Time (TBT) | 30 ms |
| Cumulative Layout Shift (CLS) | 0 |
| Speed Index | 0.8 s |

### Lighthouse Report Screenshot

![Lighthouse audit results: Performance 99, Accessibility 100, Best Practices 100, SEO 100](screenshots/lighthouse-report.png)

## 📂 Project Structure

```text
tsg-webdev-p02-anamkhan/
├── README.md
├── screenshots/
│   ├── homepage-desktop.png
│   └── lighthouse-report.png
└── forge-landing/
    ├── index.html
    ├── package.json
    ├── tailwind.config.js
    ├── src/
    │   └── input.css
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── script.js
    └── fonts/
        ├── anton-latin-400-normal.woff2
        ├── inter-latin-400-normal.woff2
        ├── inter-latin-600-normal.woff2
        └── inter-latin-700-normal.woff2
```

## 💻 Run Locally

1. Install [Node.js](https://nodejs.org/) if you want to rebuild the CSS.
2. Open a terminal in the `forge-landing` directory.
3. Install dependencies:

   ```bash
   npm install
   ```

4. Rebuild the CSS when needed:

   ```bash
   npm run build
   ```

5. Open `index.html` with VS Code Live Server or another local static server.

The prebuilt `css/styles.css` is included, so the page can be previewed without rebuilding the CSS first.

## 📱 Responsive Screenshots

- **Desktop:** `screenshots/homepage-desktop.png` — included
- **Lighthouse report:** `screenshots/lighthouse-report.png` — included
- **Mobile and tablet screenshots:** add these after capturing the page at your target viewport sizes.

## ✅ Submission Checklist

- [x] Live website link included
- [x] GitHub repository link included
- [x] Desktop homepage screenshot embedded in this README
- [x] Lighthouse report screenshot embedded in this README
- [x] Lighthouse scores and key metrics documented
- [ ] Add mobile and tablet screenshots if required for submission
- [ ] Confirm all interactive sections on desktop and mobile

## 🙌 Credits

Third-party images, icons, fonts, and other assets should be credited to their original creators/providers where required.

---

<div align="center">

**FORGE STRENGTH STUDIO**  
*Build strength. Build consistency.*

</div>
