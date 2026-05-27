# Orbit Services

<p align="center">
  <img src="assets/dashboard-card-0cEMD3Co.jpg" alt="Orbit Services preview" width="820" />
</p>

<p align="center">
  A sleek, premium multi-page website for an automation and web systems agency.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#pages">Pages</a> •
  <a href="#running-locally">Run Locally</a> •
  <a href="#project-structure">Structure</a>
</p>

---

## Overview

Orbit Services is a visually rich, animated marketing site built to present intelligent automation, workflow systems, and modern web solutions with a strong first impression. It is designed to feel polished, modern, and conversion-focused for visitors landing on GitHub or opening the live site.

## Features

- Premium hero section with bold messaging and strong visual hierarchy
- Smooth, motion-driven sections with a modern SaaS aesthetic
- Multi-page navigation for a complete business website experience
- Responsive layout for desktop and mobile screens
- Clear calls to action for service inquiries and project discovery
- Static site structure that is easy to host anywhere

## Pages

- `index.html` - Home page
- `about.html` - About page
- `services.html` - Services page
- `projects.html` - Projects / portfolio page
- `contact.html` - Contact page

## Running Locally

This is a static website, so you do not need a build step.

### Option 1: Python local server

From the project root, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Option 2: VS Code Live Server

If you use the Live Server extension, open `index.html` and start Live Server from VS Code.

### Option 3: Open directly

You can also open `index.html` directly in your browser, but a local server is recommended for the best experience.

## Project Structure

```text
Orbit-Services/
├── index.html
├── about.html
├── services.html
├── projects.html
├── contact.html
├── robots.txt
├── ~flock.js
└── assets/
    ├── *.js
    ├── *.css
    └── images
```

## Notes

- This project appears to be a static export, so there is no `package.json` or framework build pipeline in the current folder.
- Assets are already included in the repository, so deployment is as simple as uploading the folder to any static host.

## Deployment

You can host this site on GitHub Pages, Netlify, Vercel static hosting, or any standard web server.

## Contact

If you want to make Orbit Services feel even more brand-heavy, you can add a logo, live project links, or a custom domain before publishing.