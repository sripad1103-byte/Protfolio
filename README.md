# F1 Portfolio — Anirudh Bhogaraju

An interactive, F1-themed portfolio site built as a driving experience: scroll to move a car around a Las Vegas-inspired street circuit, hit pit stops to explore experience/projects/skills, and use the in-site "Team Radio" terminal to ask about my background.

**Live site:** [anirudh-bhogaraju-portfolio.netlify.app](https://anirudh-bhogaraju-portfolio.netlify.app)

## Features

- **Scroll-driven race**: scrolling moves an SVG car along a custom street circuit path, with live sector/lap tracking in the HUD
- **Pit stops**: interactive markers along the track open a sidebar with details on experience, projects, skills, education, and publications
- **Team Radio terminal**: a command-line-style widget (`$ RADIO`) supporting commands like `about`, `skills`, `experience`, `projects`, `education`, `contact`, and a couple of easter eggs
- **Lights-out intro sequence**: F1-style starting lights animation on load
- **Onboarding overlay**: brief on-load instructions for first-time visitors covering the scroll/pit-stop and radio interactions

## Tech Stack

- Vanilla HTML, CSS, and JavaScript — no frameworks or build tools
- Hand-built SVG track path and car model
- Canvas-based starfield and speed-line effects
- Custom CSS variables for theming (Barlow Condensed / Barlow / Share Tech Mono fonts)

## Running Locally

This is a single self-contained `index.html` file — no dependencies or build step required.

```bash
git clone https://github.com/sripad1103-byte/f1-portfolio.git
cd f1-portfolio
open index.html   # or just double-click the file
```

## Contact

- **LinkedIn:** [linkedin.com/in/anirudhbhogaraju](https://linkedin.com/in/anirudhbhogaraju)
- **GitHub:** [github.com/sripad1103-byte](https://github.com/sripad1103-byte)
- **Email:** anirudh.bhogaraju@rutgers.edu
