# IT Club Landing Page

<p align="center">
  <img src="src/img/logo-clubit.png" alt="IT Club Logo" width="96" height="96" />
</p>

Landing page for an IT community/club that blends design and programming. The page highlights the club vision, showcases activities, and invites visitors to join.

> [!NOTE]
> This is a static site (HTML + CSS) with a small inline script for the mobile sidebar. No build step or package manager is required.

## Features

- Hero section with primary call-to-action
- Gallery showcase and club vision statement
- Feature cards for design and programming tracks
- Discover section with large imagery and storytelling
- Responsive navigation with mobile sidebar

## Tech Stack

- HTML5
- CSS3
- JavaScript (inline for sidebar interactions)
- Font Awesome (icons)
- Google Fonts (Inter)

## Project Structure

```
.
├─ index.html
├─ style.css
├─ asset/                 # Gallery and feature images
└─ src/img/               # Logo and section visuals
```

## Getting Started

Open `index.html` directly in your browser, or serve it with any static server.

Example using VS Code Live Server:

1. Install the Live Server extension.
2. Right click `index.html` → "Open with Live Server".

## Customization

- Update content and sections in `index.html`.
- Adjust colors, typography, and layout in `style.css` (`:root` variables at the top).
- Replace images in `asset/` and `src/img/` with your own.

> [!TIP]
> If you add or remove navigation links, make sure the section IDs in `index.html` match the anchors.

## Deployment

This site can be hosted on any static hosting provider (GitHub Pages, Netlify, Vercel static, or your own web server).
