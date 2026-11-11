# The United Church of Bacon

**In Bacon We Trust.** A wholly fictional, Gothic-cathedral-inspired bacon appreciation website and fourth portfolio demo.

## What's inside

- `index.html` — the Sanctuary (homepage)
- `commandments.html` — ten sacred commandments
- `groanings.html` — 18 expandable groan-worthy jokes
- `recipes.html` — four expandable, practical recipes
- `confessional.html` — six fictional case files and their hilarious penances
- `join.html` — imaginary ranks and a CSS-only honorary pledge
- `assets/css/site.css` — all styling, breakpoints and animations
- `assets/images/` — original stained-glass image, emblem illustrations, favicon and a portfolio cover

**Technical constraints:** HTML + CSS only. No JavaScript, backend, database, build step, forms that transmit personal information, or paid dependencies. All artworks are included locally. The only external resources are the user-selected **Cormorant Garamond** and **Inter** Google Fonts. Fallback fonts are supplied.

## Preview locally

Unzip the project and double-click `index.html`. You should be able to follow every page link directly. A web server is not required for these static files.

## Publish on GitHub Pages

Keep the entire folder together, like this:

```text
deeps951.github.io/
├── index.html                   # your existing portfolio — DO NOT replace
├── assets/
├── livingcolour/
├── cafe-website/
├── hinterland-sessions/
└── united-church-of-bacon/       # copy this entire folder here
    ├── index.html
    ├── commandments.html
    ├── groanings.html
    ├── recipes.html
    ├── confessional.html
    ├── join.html
    └── assets/
        ├── css/site.css
        └── images/...
```

The demo then lives at:

`https://deeps951.github.io/united-church-of-bacon/`

You can commit and push the new directory through GitHub Desktop. No special GitHub Pages configuration is required beyond your existing working setup.

## Add a fourth project to your portfolio

1. Preview the new demo and make sure you like it.
2. Copy `united-church-of-bacon/assets/images/portfolio-cover.webp` to your portfolio's root `assets/images/` folder and rename it to `bacon-church-cover.webp` if desired.
3. Add a fourth card to your existing `Selected Work` carousel, using the homepage link `united-church-of-bacon/index.html` and cover image path `assets/images/bacon-church-cover.webp`.
4. Adjust your carousel card count / navigation labels and any hardcoded total number of projects.

I intentionally **did not** include an automatic replacement for your root portfolio homepage or its stylesheet: you have a separately maintained carousel layout, and overwriting it without your latest files could break it.

## Accessibility and use

- Semantic HTML landmarks, skip link, heading hierarchy, image alt text, focus styles, and responsive layout.
- Menu, joke cards, recipe instructions and confessions use native HTML `<details>` / `<summary>` elements.
- The membership pledge uses a CSS-only checkbox and doesn't submit, save, or track anything.
- All fictional membership ranks, church claims and confessions are parody, not an actual religious organisation, endorsement or service.
- Recipe directions are illustrative; use safe cooking practices. Never put water on burning cooking oil or fat.
- This is a demonstration, not an e-commerce, email, account or booking system.

## Original artwork

The site includes vector emblems created for this project and a cropped, optimised stained-glass cathedral illustration from the concept artwork commissioned during this collaboration. No third-party stock images are required.
