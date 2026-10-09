# Tuan Lima — Portfolio

[View the portfolio](https://tuanlima.netlify.app/) · [GitHub Pages mirror](https://tuanclima.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/tuanlima)

My personal portfolio, bringing together eight years of engineering experience across web, mobile, data and AI products. Selected work includes an Outlook add-in for Veritext, the ViX streaming platform, an AI video editor, and personal projects.

## Design and implementation

- Responsive layout with light and dark themes.
- Project case studies, experience, education and contact sections.
- Screenshots and illustrations stored locally in `assets/`.
- A single HTML document with inline CSS and JavaScript; no framework, dependency installation or build step.
- Semantic sections, descriptive image text and reduced-motion styling.

The professional case studies describe my contributions to team projects. Client source code is private. Atomation's source is public; Leruna is described without linking its private repository.

## Run locally

```bash
git clone https://github.com/TuanCLima/portfolio.git
cd portfolio
python3 -m http.server 4321
```

Open [localhost:4321](http://localhost:4321). Edit `index.html` for content, styling and interactions; replace or add images in `assets/`. `favicon.svg` provides the site icon, and `.nojekyll` allows GitHub Pages to serve the static files directly.

## Repository map

| Path | Purpose |
| --- | --- |
| `index.html` | Complete page, metadata, styles and interactions |
| `assets/` | Project screenshots and social preview image |
| `favicon.svg` | Site icon |
| `.nojekyll` | Static GitHub Pages serving |

## License

No open-source license is currently declared for this portfolio. Project screenshots and third-party brand assets retain their respective owners' rights.
