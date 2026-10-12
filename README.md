# FORGE Strength Studio
### Responsive Business Landing Page | The Sky Gen — Web Development Project 02

A modern, responsive landing page concept for **FORGE Strength Studio**, a boutique strength-training studio in Clifton, Karachi. The website is designed to communicate a premium fitness experience through bold typography, a clean layout, clear service and pricing sections, and conversion-focused calls to action.

---

## Project Overview

**Business concept:** A boutique strength-training studio offering structured training programs in a focused, supportive environment.

**Project goal:** Build a polished business landing page that presents the studio, explains its services and membership options, establishes trust through testimonials, and makes it easy for visitors to get in touch.

## Features

- **Responsive navigation** with a mobile-friendly menu and section links
- **Hero section** with a clear headline and call to action
- **Services section** with six training/service cards
- **Pricing section** with three membership plans and a highlighted recommended plan
- **Testimonials carousel** to showcase customer feedback
- **FAQ accordion** with six frequently asked questions
- **Contact section** with a front-end validated form and embedded Google Map
- **Footer** with business information and quick links
- **Responsive layout** designed for desktop, tablet, and mobile screens
- **Lightweight interactions** powered by vanilla JavaScript

> Note: The contact form is front-end functionality. It will not send or store enquiries unless a backend or form-handling service is connected.

## Technology Stack

- HTML5
- Tailwind CSS 3
- Vanilla JavaScript
- Google Maps Embed
- Git and GitHub
- Netlify (deployment option)

## Project Structure

```text
forge-landing/
├── index.html
├── package.json
├── tailwind.config.js
├── src/
│   └── input.css
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── fonts/
│   ├── anton-latin-400-normal.woff2
│   ├── inter-latin-400-normal.woff2
│   ├── inter-latin-600-normal.woff2
│   └── inter-latin-700-normal.woff2
└── screenshots/
    ├── mobile-375.png
    ├── tablet-768.png
    └── desktop-1440.png
```

*The screenshot files listed above should be added to the `screenshots/` folder after capturing them at the specified viewport sizes.*

## Run Locally

1. Install [Node.js](https://nodejs.org/) if it is not already installed.
2. Open a terminal in the `forge-landing` project directory.
3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Build the CSS:

   ```bash
   npm run build
   ```

5. Start the local static server:

   ```bash
   npm run serve
   ```

6. Open the local URL shown in the terminal.

## Deployment

This project can be deployed using Netlify or another static hosting provider.

- **Live website:** `ADD_YOUR_DEPLOYED_WEBSITE_URL`
- **GitHub repository:** `ADD_YOUR_GITHUB_REPOSITORY_URL`

Replace the placeholders above with your actual public links after deployment.

## Screenshots

Add screenshots of the responsive website to the `screenshots/` folder and update the links below.

| Viewport | Screenshot |
|---|---|
| Mobile — 375 px | `screenshots/mobile-375.png` |
| Tablet — 768 px | `screenshots/tablet-768.png` |
| Desktop — 1440 px | `screenshots/desktop-1440.png` |

## Quality Checks

Before submission:

- [ ] Test navigation and all interactive elements.
- [ ] Check the layout at mobile, tablet, and desktop widths.
- [ ] Confirm the deployed site loads from a public/incognito browser session.
- [ ] Run Lighthouse in Chrome DevTools and save the actual report as a PDF or screenshot.
- [ ] Add the three responsive screenshots.
- [ ] Replace the website and repository URL placeholders above.
- [ ] Verify all links before submitting.

**Lighthouse note:** Add your actual Lighthouse results after running the audit on the deployed website. Do not report estimated scores as measured results.

## Credits

- Third-party images, icons, fonts, and other assets should be credited to their original creators/providers where applicable.
- Google Maps is embedded for location context.

## License

Created as an educational web development project for The Sky Gen Project 02.
