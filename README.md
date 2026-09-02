# Utkarsh Tewari — Personal Site

A responsive, one-page portfolio for sharing Utkarsh's background in robotics,
technology, and independent projects.

**[View the live site](https://utkarshtewari24.github.io/stardance-personal-site/)**

## Features

- A short introduction and background section
- A robotics section covering VEX competition experience and autonomous work
- Project cards for hardware, community, and education projects
- Sticky, in-page navigation for jumping between sections
- A responsive layout that adapts to phones, tablets, and desktops
- No framework, build step, or package installation required

## Run locally

### Requirements

- A modern web browser
- Python 3 (only needed to start a local development server)

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/UtkarshTewari24/stardance-personal-site.git
   ```

2. Move into the project folder:

   ```bash
   cd stardance-personal-site
   ```

3. Start a local server:

   ```bash
   python3 -m http.server 8000
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

Because this is a static site, you can also open `index.html` directly in a
browser. Using a local server is recommended while editing the project.

## Customize the site

- Update the biography, project descriptions, and contact links in
  [`index.html`](index.html).
- Change colors, spacing, and responsive behavior in
  [`style.css`](style.css).
- Replace or reuse [`star.svg`](star.svg) for additional visual details.

## Project structure

```text
.
├── index.html  # Page content and structure
├── style.css   # Visual design and responsive styles
└── star.svg    # Reusable star illustration
```

## Built with

Plain HTML and CSS. The site is deployed with GitHub Pages.
