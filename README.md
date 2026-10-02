# Muhammad Ahmad | Software Engineer Portfolio

A fast, single-file portfolio website for Muhammad Ahmad, a software engineer who builds **WordPress sites, business websites, landing pages and custom web applications**.

- X: [@BuildWithAhmad_](https://x.com/BuildWithAhmad_)
- LinkedIn: [Muhammad Ahmad](https://www.linkedin.com/in/muhammad-ahmad-8379863b8)

## Features

- Single HTML file with no build step and no dependencies
- Sections: Hero, Services, Selected work, Process, Skills, Contact
- Light and dark mode with a sliding switch (follows the device setting and remembers the visitor's choice)
- Mobile friendly, with a hamburger menu and full-width buttons on small screens
- Text selection disabled across the page
- Keyboard focus styles and reduced-motion support

## Project files

| File | Purpose |
| --- | --- |
| `portfolio.html` | The complete website (HTML, CSS and JavaScript) |

## Run locally

1. Download `portfolio.html`.
2. Open it in any browser.

Fonts (Google Fonts) load from the internet. Offline, the page falls back to system fonts.

## Customize

- **Colors:** edit the variables at the top of the `<style>` block. Light colors are in `:root`, dark colors are in the two dark-mode blocks below it.
- **Text:** all content is plain HTML inside `<main>`.
- **Selected work:** replace the three sample cards in the `#work` section with real projects (title, result, link).
- **Links:** search for `x.com/BuildWithAhmad_` and `linkedin.com/in/muhammad-ahmad-8379863b8` to update social links.
- **Skills:** edit the list items inside the `#skills` section.

## Deploy

Rename `portfolio.html` to `index.html`, then upload it to any static host:

- **Netlify:** drag and drop the file at app.netlify.com/drop
- **Vercel:** import the folder as a static project
- **GitHub Pages:** push to a repository and enable Pages in the repository settings
- **Any hosting (cPanel etc.):** upload `index.html` to `public_html`

## Notes

- Disabling text selection is done with CSS and only deters casual copying. Page source and screenshots are still available to anyone who wants them.

## License

© 2026 Muhammad Ahmad. All rights reserved.
