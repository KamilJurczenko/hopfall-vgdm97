# hopfall-vgdm97

> A [RevealJS](https://revealjs.com/) presentation for a **15-minute talk** about the video game **Hopfall**.

## 🎮 About

This repository contains the slides for a 15-minute game dev talk covering:

- Game concept & core mechanics
- Level design philosophy
- Visual & audio design
- Technical stack
- Playtesting insights
- Lessons learned & roadmap

## 🚀 Running Locally

Install dependencies (required — RevealJS is loaded from `node_modules`):

```bash
npm install
npm start
```

Then visit `http://localhost:3000`.

> **Note:** You can also open `index.html` directly in a browser after running `npm install`, but a local server is recommended for the best experience.

## 🧾 Exporting To PDF

Reveal.js PDF export is now configured in the deck.

1. Install dependencies:

```bash
npm install
```

2. Export directly to PDF:

```bash
npm run export:pdf
```

This generates `hopfall-slides.pdf` in the project root.

Manual browser export is also available:

1. Start the local server with `npm start`.
2. Open `http://localhost:3000/?print-pdf`.
3. Print the page to PDF from your browser (`Ctrl+P`) using background graphics enabled.

## 🎹 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` / `Space` | Next slide |
| `←` | Previous slide |
| `F` | Fullscreen |
| `S` | Speaker notes view |
| `O` | Slide overview |
| `B` | Blackout screen |
| `?` | All shortcuts |

## 📁 Structure

```
hopfall-vgdm97/
├── index.html       # Main presentation (16 slides, ~15 min)
├── css/
│   └── hopfall.css  # Custom pixel-art / game theme
├── assets/          # Screenshots, GIFs, logos (add your own)
├── package.json     # Optional: local dev server
└── README.md
```

## 📝 Customising

- **Slide content** — edit `index.html`; each slide is a `<section>` block with a comment header.
- **Theme colours** — tweak CSS variables at the top of `css/hopfall.css`.
- **Assets** — drop screenshots / GIFs into `assets/` and reference them with `<img>` tags.
- **Speaker notes** — add `<aside class="notes">…</aside>` inside any `<section>`.
