# Responsive Personal Portfolio Website

A clean, modern and fully responsive personal portfolio built from scratch with HTML5, CSS3 and vanilla JavaScript. No frameworks or templates.

**Live demo:** _add your GitHub Pages link here_

## Features

- **Home** – name, short introduction and welcome message with call-to-action buttons
- **About Me** – education, interests and career goals
- **Skills** – animated progress bars that fill as you scroll
- **Projects** – three project cards with descriptions, tech tags and links
- **Contact** – form with JavaScript validation (name, email format, message length) and inline error messages
- **Responsive** – mobile, tablet and desktop layouts (CSS Grid, Flexbox, media queries)
- **Navigation** – fixed header, smooth scrolling, active-section highlight, hamburger menu on mobile
- **Extras** – light/dark theme (saved in `localStorage`), scroll-reveal animations, skip link, ARIA labels and reduced-motion support

## Technologies

- HTML5 (semantic elements)
- CSS3 (custom properties, Grid, Flexbox, media queries)
- JavaScript (ES6, IntersectionObserver, DOM events)
- Git & GitHub

## Project Structure

```
.
├── index.html
├── style.css
├── script.js
├── README.md
└── screenshots/
    ├── desktop.png
    └── mobile.png
```

## Setup

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```
2. Open `index.html` in any modern browser, or serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit http://localhost:8000.

## Deploying with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site will be live at `https://your-username.github.io/portfolio/`.

## Customising

Replace the following with your own details in `index.html`:

- Name (title tag, hero heading, footer, logo initials)
- Education entries, interests and career goals
- Skill percentages
- Project titles, descriptions and links
- Email address and GitHub link in the Contact section

## Screenshots

| Desktop | Mobile |
| --- | --- |
| ![Desktop](screenshots/desktop.png) | ![Mobile](screenshots/mobile.png) |

## Contact form note

The form validates input in the browser. It does not send email because there is no backend. To receive messages, connect a service such as Formspree or EmailJS in the submit handler in `script.js`.
