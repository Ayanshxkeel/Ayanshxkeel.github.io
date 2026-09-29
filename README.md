# Ayan Shakeel — Portfolio

The source for [ayanshxkeel.github.io](https://ayanshxkeel.github.io/), a one-page portfolio for my experience, skills, and selected software, data, and physical computing projects.

## Sections

- **Introduction:** Waterloo mathematics and a featured ImpactIQ prototype.
- **Experience:** Government of Ontario, CORDAX, BIASafe AI, and NexCreative.
- **Projects:** Selected software and data projects, each linking to its source repository.
- **Skills and contact:** Technical tools, email, GitHub, and LinkedIn.

## How it is built

This is a static HTML and CSS site with small JavaScript scroll effects. There is no framework, server, database, analytics tracker, or build step. The layout adapts to smaller screens with CSS media queries. GitHub Pages publishes `index.html` from the `main` branch.

## Run locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Make a change

The page text and project links are in `index.html`. The dark palette, layout refinements, and motion are in `theme.css`; the base styles are in the `<style>` block. Edit the file, preview it locally, then commit and push to `main`; GitHub Pages will publish the new version. Project demonstrations are linked only when they have a working public deployment; the current cards link to code.
