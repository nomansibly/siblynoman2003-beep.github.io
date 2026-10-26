# Sibly Noman — Engineering × Data

[Visit the interactive portfolio](https://siblynoman2003-beep.github.io/)

A responsive, accessible professional portfolio showcasing mechanical engineering, numerical simulation, research and project leadership.

## Features

- Filterable project gallery with live ThermoDC and Indoor Air Lab links.
- Interactive heat/airflow energy-balance calculator with explicit assumptions.
- Persistent light/dark theme, reduced-motion support and keyboard focus indicators.
- Education, research milestones and project management experience.
- Buildless HTML, CSS and JavaScript; no external libraries, analytics or API keys.

## Run locally

```bash
python -m http.server 8000
```

Open http://localhost:8000. GitHub Pages publishes `index.html` from the root of `main`.

## Maintenance

Edit `index.html` to update content, styles or project links. Professional background is based on author-supplied information; repository project descriptions were checked against their READMEs. Concept projects are distinguished from executed numerical work. Do not present illustrative graphics or the mini calculator as validated simulation results.

## Mini lab

`temperature rise = heat load (kW) × 1000 / (1.2 × airflow (m³/s) × 1005)`

Assumes constant air properties and complete sensible heat transfer. No equipment selection or operational safety claims.
