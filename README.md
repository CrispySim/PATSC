# PATSC website

Static site for the Paediatric Advanced Trauma Skills Course. Plain HTML and CSS, no build step.

## Structure
- `index.html` home page
- `about/`, `faculty/`, `booking/`, `testimonials/`, `faq/`, `contact/`, `links/`, `pre-course/` each contain an `index.html`
- Styling is built into each page (CSS variables at the top of the `<style>` block). `assets/` holds the logo (white and dark versions), favicon and photos

## Deploying on GitHub Pages
1. Upload everything in this folder to the root of the repository (keep the folders).
2. Settings > Pages > Deploy from a branch > `main` / root.
3. After 1-2 minutes, hard refresh (Ctrl+Shift+R).

## Editing
- Placeholders are highlighted in lilac and start with `[`. Search for `todo` to find them all.
- Colours are the variables at the top of each page's `<style>` block (same in every file).
- Photos: add files to `assets/` and replace each `<div class="photo">` with an `<img>` tag.
