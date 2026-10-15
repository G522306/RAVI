# Sentry website

Single-page marketing site for Sentry, the just-in-time access gateway for production Postgres. Plain HTML, no build step.

## Deploy on Render

1. In Render, choose **New > Static Site** and pick this repository (or **New > Blueprint** to use `render.yaml`).
2. Leave the build command empty and set the publish directory to `.`.
3. Deploy. Render serves `index.html` at the site root.

## Edit locally

Open `index.html` in a browser. Everything (CSS and JS) is inline; fonts load from Google Fonts.
