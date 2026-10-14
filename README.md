# Firoz Hussain — Portfolio

A responsive portfolio for a Java Full Stack Developer specializing in enterprise banking, Spring Boot microservices, and Angular applications.

## Live website

**https://Firoz1212.github.io/firoz-portfolio/**

## Features

- Dark visual design with lime accents and responsive layouts.
- Enterprise banking case studies covering liquidity management, digital transaction banking, and NBK engagements.
- Technical skills, professional experience, education, and awards.
- Expandable project details and conceptual workflow diagrams.
- Downloadable resume, email contact, LinkedIn, and GitHub links.
- Keyboard focus indicators, a skip link, and reduced-motion support.

## Technology

HTML5, CSS3, and vanilla JavaScript. No build step or package installation is required. Google Fonts supplies DM Sans and Space Grotesk, with local font fallbacks.

## Project structure

```text
dist/
  index.html                   # Page content and sections
  style.css                    # Theme and responsive layout
  script.js                    # Copy-email interaction
  Firoz-Hussain-Resume.pdf      # Downloadable resume
.github/workflows/deploy.yml    # Automatic GitHub Pages deployment
```

## Run locally

From the repository root:

```bash
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173 in a browser.

## Update the portfolio

Edit content in `dist/index.html`, styles in `dist/style.css`, and interactions in `dist/script.js`. Replace the resume PDF while retaining its filename to keep download links working.

```bash
git add dist README.md
git commit -m "Update portfolio"
git push origin main
```

## Deployment

In repository **Settings → Pages**, select **GitHub Actions** as the source. The workflow uploads `dist/` and deploys it to GitHub Pages on every push to `main`. It can also be started manually from the Actions tab. Deployment status and the published URL appear in the workflow run.

## Project context

Enterprise engagements were completed as part of employment at Intellect Design Arena. Diagrams are conceptual illustrations; the repository does not contain proprietary banking source code or client interfaces.

## Contact

- Email: firoz.hussain004@gmail.com
- LinkedIn: https://linkedin.com/in/firoz-hussain
- GitHub: https://github.com/Firoz1212
