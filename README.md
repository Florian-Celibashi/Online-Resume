# Florian Celibashi — Portfolio

A fast, responsive, recruiter-facing portfolio for Florian Celibashi. The site highlights selected software and AI work, relevant experience, technical strengths, work authorization, and direct contact paths.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 4173
```

Then open [http://localhost:4173](http://localhost:4173).

## Structure

- `index.html` — page content and metadata
- `styles.css` — responsive layout and visual system
- `script.js` — lightweight scroll-state and reveal behavior
- `resume.pdf` — downloadable résumé
- `og.png` — social-sharing preview

## Deployment note

This is a static site and can be deployed directly to Vercel. The previous root-to-PDF redirect has been removed so the portfolio page loads first; the résumé remains available at `/resume.pdf`.
