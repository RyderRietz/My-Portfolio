# Ryder Rietz — Personal Portfolio

A professional single-page landing page per PRD.md and STANDARDS.md.

## File Structure

- `index.html` — Semantic HTML5 single-page site
- `style.css` — Vanilla CSS3 (Flexbox/Grid), no frameworks
- `images/headshot.jpg` — Profile photo
- `resume.pdf` — Downloadable resume
- `PRD.md` — Product requirements
- `STANDARDS.md` — Design & technical standards

## Design

- Color palette: `#CE1141` red accents, black text, white background
- Font: Inter (Google Fonts)
- Fully responsive (mobile + desktop)

## Sections

1. Sticky header / nav with Resume CTA
2. Hero — headshot, name, bio, LinkedIn/GitHub buttons
3. Projects — Houston Rockets data mining project (BAIS:3500)
4. Skills — Python, SQL, R, Azure, Excel, Data Mining
5. Resources — Resume download, LinkedIn, GitHub
6. Contact bar — email CTA
7. Footer

## Dev Server

- Workflow: "Start application" runs `python3 -m http.server 5000 --bind 0.0.0.0`
- Port: 5000

## Deployment

- Configured as static site (`publicDir: "."`)
