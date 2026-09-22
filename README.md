# Intelligent Health Research Lab (IHR Lab) — Website

Static site for the Intelligent Health Research Lab, Department of Health Services
Administration & Policy, College of Public Health, Temple University.
Plain HTML/CSS — no build step required. Deploys on GitHub Pages as-is.

## Pages
- `index.html` — Home (mission, vision, research areas)
- `projects.html` — Funded projects
- `publications.html` — Peer-reviewed publications
- `resources.html` — Tools & datasets
- `people.html` — Team (current + past researchers)
- `connect.html` — Social links & interest form
- `dream-kg.html` — Dream-KG project detail

## Design
- Shared styles in `assets/css/style.css` — Newsreader (serif) + Libre Franklin,
  Temple cherry sampled from the logo, light + dark mode with a theme toggle.
- Header (logo masthead + centered nav) and footer are identical on every page.
- Optimized images and logo assets live in `assets/img/`.

## Links (all live)
- Interest form → Qualtrics survey (Home + Connect)
- Connect: LinkedIn (`company/tuihrlab`), Instagram (`@ihrlab`), GitHub (`atomosky/ihrlab`)

## Deploying
Commit these files to the repo's Pages branch/root. To use a custom domain,
add a `CNAME` file containing only that domain (e.g. `ihrlab.temple.edu`) and
set it in the repo's Pages settings.
