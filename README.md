# Pub Atlas — Website

The marketing / waiting-list site for [Pub Atlas](https://pubatlas.co.uk), a pub-collecting app launching in London.

The site is not the product — its job is to establish the brand, explain the concept in a few seconds, and drive visitors to the waiting list ahead of launch.

## Structure

Static site, no build step or framework:

- `index.html` — the whole site (nav, hero, about, waiting list, footer). Styles are inline in a `<style>` block.
- `assets/` — images used **by the live site**: the hanging-sign logo, the app loading-screen phone mockup, the pub street-sketch illustration (plus a background-removed version used in the footer), and `favicon/` (generated icon sizes).
- `brand-reference/` — the full brand board and asset-spec sheets. Reference material for design decisions, not linked from the site itself.

## Brand

Colours, type and asset sources are documented on the brand board in `brand-reference/brand-board.png`. Headings use Fraunces, body text uses Lora, matching the app.

## Editing

Everything lives in `index.html` — sections are commented (Navigation / Hero / About / Waiting List / Footer). No templating; just edit the HTML and CSS directly and refresh.

## Known gaps

- The waiting-list email form is visual only — nothing is wired up to capture submissions yet.
- Instagram / Contact / Privacy Policy in the footer are placeholder text, not linked pages.
