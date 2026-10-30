# Andrew — GitHub Pages portfolio · HTML & CSS only

This is the redesigned personal portfolio, including two converted project demonstrations.

**Every page is written in plain HTML and CSS.** There is **no JavaScript, no Bootstrap, no Tailwind, no Django, no Node, and no build process**. Assets are local images. A browser can open `index.html` directly.

## Files

- `index.html` — responsive portfolio homepage, with three functional hero jump links (Design / Code / Rhythm)
- `assets/css/main.css` — its styles, including CSS-only mobile navigation
- `assets/images/` — locally stored, optimised homepage imagery
- `livingcolour/index.html` and `livingcolour/css/styles.css` — Living Colour project demo, converted from Bootstrap to custom CSS
- `portfolio/cafe-website/index.html` and `portfolio/cafe-website/css/styles.css` — café project demo, converted from Bootstrap to custom CSS
- `.nojekyll` — static GitHub Pages configuration

## Preview

Unzip and **double-click `index.html`** to open it in your browser. You don't need Python, Docker or a development server.

## Publish to GitHub Pages

1. Make a backup of your original repository.
2. Copy the **contents** of this project folder to the root of your `deeps951.github.io` repository (not the parent folder).
3. Commit and push to its GitHub Pages deployment branch.
4. Open `https://deeps951.github.io` after GitHub Pages publishes the update.

## Before going live

- The homepage contact button links to GitHub, because no preferred email address was supplied.
- The café and Living Colour subpages are **portfolio demonstrations**, not live booking/contact websites. Static HTML alone cannot process an enquiry form, so the old non-working forms were removed instead of pretending they worked.
- Please check the business details and permission to display the older project images, as these came from your original ZIP.
- The only code files are `.html` and `.css`. Image files and `.nojekyll` are website assets/configuration, not application code.

## Hero navigation

The three links at the bottom of the hero use ordinary HTML anchors and section IDs:

- **Design** → `#work` (selected portfolio projects)
- **Code** → `#capabilities` (development approach)
- **Rhythm** → `#beyond` (music, photography and aviation)

Smooth scrolling is defined by `scroll-behavior: smooth` in `assets/css/main.css` and switches off when a visitor has enabled reduced-motion accessibility settings. No JavaScript is involved.

### Version 3 visual refinement

The homepage project, portrait, and interest images have a 1px black border and a restrained soft drop shadow. The full-bleed hero image remains borderless. This styling is entirely CSS.
