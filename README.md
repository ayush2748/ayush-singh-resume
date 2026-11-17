# Ayush Singh - Maritime Resume Website

A responsive, single-page resume and portfolio website built for the CSS module assignment.

## Live website
https://ayush2748.github.io/ayush-singh-resume/

## Repository structure
- `docs/index.html` - semantic page structure and resume content
- `docs/styles.css` - colour palette, typography, layouts, cards, timeline and responsive styling
- `docs/script.js` - accessible mobile navigation and automatic footer year
- `docs/assets/favicon.svg` - custom initials favicon
- `.github/workflows/pages.yml` - automated GitHub Pages deployment workflow

## Run locally
Open `docs/index.html` in a browser. No build tools or package installation are required.

## Publish with GitHub Pages
1. Open **Settings -> Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` deploys the contents of `docs/` whenever code is pushed to `main`, or when manually started from the Actions tab.
4. After the workflow succeeds, visit the live website link above.

## Design decisions
The website uses a restrained maritime palette: deep navy, sea green, soft mint, warm ivory and a small orange accent. DM Sans is used for body copy and Playfair Display for headings. Flexbox aligns the navigation and utility rows; CSS Grid structures the hero, highlights, experience, education and skills. Element, class and ID selectors organise the styling. Responsive breakpoints adapt the layout for mobile, with keyboard focus, a skip link and reduced-motion support.

## Accuracy note
The portfolio uses the education and sea-service details supplied for this assignment. Verify credential names and validity against original documents before using the site as a formal employment CV.