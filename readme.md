<h1 align="center">⚡ AreadmeForge</h1>

<p align="center">
  <em>Build a polished GitHub profile README in the browser — live preview, one HTML file, no build step.</em>
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/AreadmeForge/"><img src="https://img.shields.io/badge/Live_app-GitHub_Pages-222222?logo=githubpages&logoColor=white" alt="Live app on GitHub Pages" /></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/build-none-0D9488" alt="No build step" />
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/AreadmeForge/"><strong>🚀 Open the app →</strong></a>
</p>

---

## Overview

AreadmeForge is a single-page, client-side generator for GitHub profile READMEs. Fill in your details, pick your stack and widgets, and download a ready-to-commit `README.md` for your `<username>/<username>` repository. Nothing is sent to a server; the only network requests are for fonts, the Markdown renderer, and the badge/widget images in the preview.

## Features

- **Identity** — name, GitHub username, headline, typing-animation roles, tagline, and an "about" bullet list
- **Accent color** — 6 preset swatches or any color from a picker
- **Tech-stack picker** — 11 skills with [devicon](https://devicon.dev/) icons (Flutter, Dart, Rust, C++, Python, JavaScript, Git, Linux, Firebase, Docker, Figma)
- **Social badges** — GitHub, website, YouTube, email, LinkedIn, Telegram, X, Instagram as [shields.io](https://shields.io/) badges; only filled-in links are exported
- **Widgets** (toggle each on/off):
  - Wave header/footer — [capsule-render](https://github.com/kyechan99/capsule-render)
  - Typing header — [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg)
  - Stats + top languages — [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
  - Streak — [github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)
  - Trophies — [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy)
  - Contribution snake — [Platane/snk](https://github.com/Platane/snk) (needs the snk workflow in your profile repo)
  - Profile views — [komarev/ghpvc](https://github.com/komarev/ghpvc)
- **Preview / Raw tabs** — rendered preview (via [marked](https://marked.js.org/)) or raw Markdown
- **Copy** to clipboard or **download** `README.md` (also `Ctrl/⌘ + S`)
- Responsive dark UI

## Tech Stack

| Layer | Technology |
|---|---|
| App | HTML5, CSS3, vanilla JavaScript — all in `index.html` |
| Markdown preview | marked 12 via jsDelivr |
| Icons & badges | devicon, shields.io |
| Fonts | Inter, JetBrains Mono via jsDelivr |

## Getting Started

Use it online: **https://aghorbani84.github.io/AreadmeForge/**

Or run it locally:

```bash
git clone https://github.com/aghorbani84/AreadmeForge.git
cd AreadmeForge
python3 -m http.server 8000   # then visit http://localhost:8000
```

### Publishing your profile README

1. Fill in the form and choose your widgets.
2. Click **Download** (or press `Ctrl/⌘ + S`).
3. Create a public repository named exactly like your GitHub username.
4. Commit the downloaded `README.md` to its root — it appears on your profile.

## Project Structure

```
.
├── index.html   # The whole app (HTML, CSS, JS)
└── readme.md
```

## Acknowledgments

Widget images are served by the open-source projects linked above; thanks to their authors.

## Author

**Abolfazl Ghorbani** — [@aghorbani84](https://github.com/aghorbani84)
