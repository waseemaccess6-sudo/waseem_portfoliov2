# Waseem Ali — Automation Portfolio

A no-build, responsive multi-page portfolio built with semantic HTML5, CSS, and vanilla ES6 JavaScript.

## Run locally

Because the header and footer are loaded as partials with `fetch()`, serve the folder through a local HTTP server instead of opening `index.html` directly.

```bash
python -m http.server 8080
```

Then open `http://localhost:8080/`.

## Pages

- `index.html` — landing page
- `services.html` — six service offerings
- `portfolio.html` — eight portfolio projects with category filters and detail modals
- `skills.html` — categorized skill matrix
- `pricing.html` — three pricing tiers + accordion
- `faq.html` — 13 FAQ items
- `contact.html` — validated proposal form + contact details

## Customization

Main design tokens live in `assets/css/styles.css` under `:root`. Portfolio data is in `assets/js/data.js`. Replace placeholder social/phone links in the HTML and add a real resume PDF if desired.

## Contact form delivery

The form currently performs front-end validation and displays a success toast. For production submissions, connect the `submit` handler in `assets/js/app.js` to your Formspree endpoint, Netlify Forms, Zapier Webhook, n8n webhook, or a custom backend.

## Deployment

This site can be deployed directly to Netlify, Vercel static hosting, GitHub Pages, or conventional static hosting. No build step is required.
