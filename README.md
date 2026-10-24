# camdengoff.com

Personal site for freelance video and church website tools. Plain HTML/CSS, no build step.

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000.

## To customize

- `index.html`: replace the placeholder tool cards, project thumbnails, and About text.
- Contact form: point `action` at a Formspree or Netlify Forms endpoint to receive submissions by email (it currently opens the visitor's mail app).
- `styles.css`: colors are CSS variables at the top.
