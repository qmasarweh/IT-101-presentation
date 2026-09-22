# IT 101: AI & Cyber

A self-contained, single-file **HTML lecture presentation site** — built in **Arabic (RTL)** with a dark neon "cyber" aesthetic — used for an IT 101 lecture on **Artificial Intelligence and Cybersecurity**.

Open `index.html` in any modern browser. No build tools, no dependencies to install.

## Features

- **Single-file deployment** — all markup and styles live in one `index.html`; just open it or host it anywhere
- **Arabic RTL layout** — `lang="ar" dir="rtl"`, Cairo typeface for Arabic text
- **Dark neon cyber theme** — grid backdrop, glassmorphism panels, neon green/cyan/pink accents (Orbitron display font)
- **Lecture-ready deck** — slide-style sections covering AI and cybersecurity topics
- **Zero setup** — fonts (Google Fonts) and icons (Font Awesome) load from CDN; everything else is inline

## How to view

```bash
# Option 1: open directly in your browser
start index.html        # Windows
open index.html         # macOS

# Option 2: serve it locally
python -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
IT-101-presentation/
└── index.html          # the entire presentation (HTML + CSS inline)
```

## Technical notes

- Pure HTML + CSS (no JavaScript frameworks, no build step)
- `user-scalable=no` viewport is intentional for kiosk/lecture-screencast display
- Internet connection required for Google Fonts and Font Awesome CDN icons

## License

[MIT](LICENSE) © Qusai Masarweh