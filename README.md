# Aman Puskar – Portfolio Website

A professional portfolio website for Aman Puskar — Full Stack Developer & GenAI Engineer.

## Features

- **Animated particle network background** — responds to mouse movement
- **Typewriter text animation** — cycles through key skills
- **Scroll-reveal animations** — smooth section transitions
- **Animated skill progress bars** — triggered on scroll into view
- **Hero counter animation** — stats count up on load
- **Mobile responsive** — hamburger menu, fluid grids
- **Active nav link highlighting** — updates on scroll

## Tech Used

- Pure HTML5, CSS3, Vanilla JavaScript
- Google Fonts: Sora + JetBrains Mono
- No frameworks, no build tools — just open `index.html`

## How to Run

Simply open `index.html` in any modern browser:

```bash
# Option 1: Double-click index.html
# Option 2: Use a local server (recommended)
npx serve .
# or
python -m http.server 8080
```

## Deploy to GitHub Pages

1. Push the files to a GitHub repo
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your site will be live at `https://username.github.io/repo-name`

## Deploy to Vercel / Netlify

Drag and drop the folder into [vercel.com](https://vercel.com) or [netlify.com](https://netlify.com) — no config needed.

## File Structure

```
aman-portfolio/
├── index.html     # Main HTML structure
├── style.css      # All styles & animations
├── script.js      # JS: particles, typing, counters, scroll fx
└── README.md      # This file
```

## Customization

- Update links, email, phone in `index.html`
- Adjust colors via CSS variables at the top of `style.css`
- Add/remove sections freely in `index.html`
