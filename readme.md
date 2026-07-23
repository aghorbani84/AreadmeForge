<p align="center">
  <img src="assets/banner.png" alt="AreadmeForge Banner" width="100%" />
</p>

<h1 align="center">⚡ AreadmeForge</h1>

<p align="center">
  <em>Forge an elite GitHub profile README in seconds — zero dependencies, zero build step, one HTML file.</em>
</p>

<p align="center">
  <a href="https://github.com/aghorbani84/AreadmeForge/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT" /></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Zero-Dependencies-green.svg" alt="Zero Dependencies" />
  <img src="https://img.shields.io/badge/Works-Offline-brightgreen.svg" alt="Works Offline" />
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/AreadmeForge/">🚀 Live Demo</a> &nbsp;·&nbsp;
  <a href="https://github.com/aghorbani84/AreadmeForge/issues">🐛 Report Bug</a> &nbsp;·&nbsp;
  <a href="https://github.com/aghorbani84/AreadmeForge/issues">✨ Request Feature</a>
</p>

---

## TL;DR

Open `index.html`, customize your identity, toggle widgets, hit **Download**, drop the resulting `README.md` into a repository named after your GitHub username, and your profile instantly looks like a senior engineer's. That's it. No Node, no Python, no Docker, no account, no telemetry.

## 📑 Table of Contents

- [🧠 About](#-about)
- [🎯 Why AreadmeForge?](#-why-areadreforge)
- [✨ Features](#-features)
- [🧩 Widget Catalog](#-widget-catalog)
- [🚀 Quick Start](#-quick-start)
- [📖 Usage Guide](#-usage-guide)
- [⌨️ Keyboard Shortcuts](#️-keyboard-shortcuts)
- [🧰 Tech Stack](#-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🏗️ How It Works](#️-how-it-works)
- [🎨 Customization Tips](#-customization-tips)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contributing](#-contributing)
- [❓ FAQ](#-faq)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)
- [👤 Author](#-author)

---

## 🧠 About

**AreadmeForge** is a single-file, zero-dependency web application that generates production-grade, GitHub-flavored `README.md` files for your personal profile or any repository. It ships with:

- A **live preview pane** that renders exactly like GitHub does
- A **themeable accent system** with 6 presets + custom color picker
- A **curated tech-stack picker** powered by devicon
- A **modular widget engine** — stats, streak, trophies, contribution snake, typing header, wave banner, profile views

Built for engineers who care about craft — people who want a profile that looks intentional, not copy-pasted from a tutorial.

## 🎯 Why AreadmeForge?

| Concern | Other generators | AreadmeForge |
|---|---|---|
| Setup | `npm install`, build, deploy | ✅ Open one HTML file |
| Telemetry / accounts | Often required | ✅ None — 100% client-side |
| Offline use | ❌ Usually broken | ✅ Works offline |
| Live GitHub-style preview | ⚠️ Sometimes | ✅ Pixel-accurate |
| Themeable accent color | ⚠️ Limited | ✅ Any hex, auto-complementary |
| Code quality | 🤷 | ✅ Vanilla, readable, no framework lock-in |
| Output | Bloated templates | ✅ Clean, commented Markdown |

## ✨ Features

- 🌊 **Wave banner** with gradient header & footer ([capsule-render](https://github.com/kyechan99/capsule-render))
- ⌨️ **Typing animation** with custom roles ([readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg))
- 📊 **GitHub stats** + top languages cards ([github-readme-stats](https://github.com/anuraghazra/github-readme-stats))
- 🔥 **Streak graph** ([streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats))
- 🏆 **Trophy case** ([github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy))
- 🐍 **Contribution snake** ([Platane/snk](https://github.com/Platane/snk))
- 👀 **Profile views counter** ([komarev/ghpvc](https://github.com/komarev/ghpvc))
- 🛠 **Tech stack picker** — 11+ curated skills with devicon badges
- 🔗 **Social links** — auto-generated shields.io badges, only filled links are exported
- 🎨 **Accent theming** — 6 presets + custom color picker with auto-complementary hue
- 👁 **Live preview** / raw markdown tabs
- 📋 **One-click copy** to clipboard
- ⬇ **Download** `README.md` with proper UTF-8 encoding
- ⌨️ **Keyboard shortcuts** (`Ctrl/⌘ + S` to export)
- 📱 **Fully responsive** — works on mobile, tablet, desktop
- 🌙 **Dark, modern UI** with glassmorphism, animated blobs, and grid backdrop
- 🚫 **Zero runtime dependencies** — only marked.js via CDN for preview rendering

## 🧩 Widget Catalog

| Widget | Source | Purpose |
|---|---|---|
| 🌊 Wave banner | [capsule-render](https://github.com/kyechan99/capsule-render) | Eye-catching header & footer |
| ⌨️ Typing header | [readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg) | Animated role showcase |
| 📊 Stats cards | [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) | Commits, PRs, stars, top langs |
| 🔥 Streak graph | [streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats) | Daily contribution streak |
| 🏆 Trophy case | [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) | Achievement showcase |
| 🐍 Snake | [Platane/snk](https://github.com/Platane/snk) | Animated contribution grid |
| 👀 Views counter | [komarev/ghpvc](https://github.com/komarev/ghpvc) | Profile view tracking |

## 🚀 Quick Start

### Option 1 — Use it online (recommended)

1. Open 👉 [AreadmeForge Live](https://aghorbani84.github.io/AreadmeForge/)
2. Fill in your identity, pick skills, toggle widgets.
3. Click ⬇ **Download** (or press `Ctrl/⌘ + S`).
4. Create a new GitHub repository named exactly like your username (e.g. `aghorbani84/aghorbani84`).
5. Upload the downloaded `README.md` to the root of that repo.
6. ✨ Visit your GitHub profile — your new README is live.

### Option 2 — Run it locally

```bash
# Clone the repository
git clone https://github.com/aghorbani84/AreadmeForge.git
cd AreadmeForge

# Open the file — that's literally it
# macOS
open index.html
# Linux
xdg-open index.html
# Windows
start index.html
```

> 💡 No `npm install`, no `pip install`, no build step. The entire app is one HTML file with embedded CSS and JS.

## 📖 Usage Guide

### 👤 Identity section

- **Display name** — shown as the `# I'm …` heading.
- **GitHub username** — used to build stats/streak/trophy/snake URLs. Must match your real username.
- **Headline** — the `### …` subheading (e.g. `Software Engineer · Flutter × Rust`).
- **Typing roles** — semicolon-separated roles for the typing animation (e.g. `Software Engineer;Flutter Developer;Rustacean 🦀`).
- **Tagline** — a one-paragraph intro used in the About Me section.
- **About bullets** — multi-line list; each line becomes a `- ` bullet.

### 🎨 Accent color

Pick a preset swatch or use the native color picker. AreadmeForge automatically derives a complementary hue for gradients (banner, buttons, glows).

### 🛠️ Tech stack

Click chips to toggle skills on/off. Selected skills are rendered as `44×44` devicon badges wrapped in links to each technology's official site.

### 🧩 Widgets

Toggle any combination of the 7 widgets. Disabled widgets are completely omitted from the output — no empty sections, no broken placeholders.

### 🔗 Socials

Only non-empty social links are exported as shields.io badges. Leave a field blank to hide it.

### Preview & Export

- Switch between **Preview** (rendered HTML) and **Markdown** (raw source) tabs.
- 📋 **Copy** — copies the raw Markdown to your clipboard.
- ⬇ **Download** — saves `README.md` with UTF-8 encoding.
- The status bar shows live character and line counts.

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + S` / `⌘ + S` | Download `README.md` |
| `Tab` | Navigate form fields |
| `Space` | Toggle focused chip / switch |

## 🧰 Tech Stack

| Layer | Technology | Why |
|---|---|---|
| Markup | HTML5 | Semantic, accessible, zero build |
| Styling | Vanilla CSS3 | CSS variables, `color-mix()`, `backdrop-filter`, grid, custom scrollbars |
| Logic | Vanilla JavaScript (ES2020+) | No framework overhead, fully readable |
| Markdown rendering | [marked.js](https://github.com/markedjs/marked) via CDN | GitHub-flavored preview |
| Typography | [Fontsource](https://fontsource.org/) (Inter + JetBrains Mono) | Privacy-friendly, no Google Fonts tracking |
| Icons / badges | [devicon](https://devicons.dev/), [shields.io](https://shields.io/) | Industry-standard vector assets |

## 📁 Project Structure

```
AreadmeForge/
├── index.html          # The entire application (HTML + CSS + JS)
├── assets/
│   └── banner.png      # Repository social preview banner
├── LICENSE             # MIT License
├── README.md           # You are here 👋
└── .github/
    └── ISSUE_TEMPLATE/ # (optional) bug & feature templates
```

> 🧠 Yes, the whole app is one file. That's the point. Fork it, edit it, host it on GitHub Pages, send it to a friend via email — it just works.

## 🏗️ How It Works

```
┌──────────────┐    input events     ┌──────────────┐
│  Form panel  │ ─────────────────▶  │   State obj  │
└──────────────┘                     └──────┬───────┘
                                           │ 120ms debounce
                                           ▼
                                    ┌──────────────┐
                                    │ buildMarkdown│
                                    │   (pure fn)  │
                                    └──────┬───────┘
                                           │
                         ┌─────────────────┼─────────────────┐
                         ▼                 ▼                 ▼
                  ┌────────────┐   ┌────────────┐   ┌──────────────┐
                  │ Live HTML  │   │ Raw MD     │   │ Download /   │
                  │ (marked)   │   │  preview   │   │ Copy actions │
                  └────────────┘   └────────────┘   └──────────────┘
```

1. Every input updates a single in-memory state object.
2. A debounced `render()` rebuilds the Markdown string from scratch (pure function — easy to test, easy to extend).
3. The Markdown is fed to marked.js for the preview pane and exposed raw for copy/download.
4. Accent color changes propagate to CSS custom properties and to the generated Markdown (banner gradients, view counter color).

## 🎨 Customization Tips

- **Add a new skill** → push a `[name, devicon-path, url]` tuple into the `SKILLS` array.
- **Add a new widget** → add a `[key, label]` entry to `WIDGETS`, a default in `DEFAULTS.widgets`, and a rendering block inside `buildMarkdown()`.
- **Add a new social** → add a `[key, label, placeholder]` to `SOCIALS` and a matching `BADGES[key]` shields.io string.
- **Change the UI theme** → edit the `:root` CSS variables (`--bg`, `--accent`, `--accent2`, `--radius`).

## 🗺️ Roadmap

- [ ] Light theme toggle
- [ ] Import / export JSON config (save your setup)
- [ ] Drag-and-drop widget ordering
- [ ] More skills (Go, Kotlin, Swift, TypeScript, AWS, Kubernetes…)
- [ ] i18n (Persian 🇮🇷, Spanish 🇪🇸, French 🇫🇷…)
- [ ] PWA install + offline caching of CDN assets
- [ ] Shareable config via URL hash (`#config=...`)
- [ ] Template gallery (minimal, maximalist, terminal-style…)

PRs welcome for any of the above — see [Contributing](#-contributing).

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contribution you make is greatly appreciated.

1. 🍴 **Fork** the repository
2. 🌿 Create your feature branch — `git checkout -b feature/amazing-thing`
3. ✏️ **Commit** your changes — `git commit -m 'feat: add amazing thing'`
4. 🚀 **Push** to the branch — `git push origin feature/amazing-thing`
5. 🎯 Open a **Pull Request**

Please follow [Conventional Commits](https://www.conventionalcommits.org/) and keep PRs focused on a single concern. For major changes, open an issue first so we can discuss the design.

## ❓ FAQ

**Q: Do I need to install anything?**
A: No. Open `index.html` in any modern browser. That's the whole setup.

**Q: Does it send my data anywhere?**
A: No. Everything runs locally in your browser. The only network requests are CDN assets (fonts, icons, preview badges) which GitHub itself will also fetch when rendering your README.

**Q: Why is my snake widget empty?**
A: The snake SVG is generated by a GitHub Action in your profile repo. Add the [Platane/snk workflow](https://github.com/Platane/snk) to your `<username>/<username>` repository and the snake will appear after the first run.

**Q: Can I use this for a project README (not a profile)?**
A: Absolutely. The output is plain GitHub-flavored Markdown — drop it anywhere.

**Q: The preview looks different from GitHub.**
A: AreadmeForge's preview mimics GitHub's dark theme. Minor styling differences (fonts, spacing) are expected; the structure and badges will render identically.

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for the full text.

> TL;DR — do whatever you want with it, just keep the copyright notice.

## 🙏 Acknowledgments

AreadmeForge stands on the shoulders of giants. Huge thanks to the maintainers of:

- [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
- [DenverCoder1/github-readme-streak-stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [DenverCoder1/readme-typing-svg](https://github.com/DenverCoder1/readme-typing-svg)
- [ryo-ma/github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy)
- [Platane/snk](https://github.com/Platane/snk)
- [kyechan99/capsule-render](https://github.com/kyechan99/capsule-render)
- [komarev/ghpvc](https://github.com/komarev/ghpvc)
- [devicons/devicon](https://github.com/devicons/devicon)
- [shields.io](https://shields.io/)
- [markedjs/marked](https://github.com/markedjs/marked)
- [fontsource/fontsource](https://github.com/fontsource/fontsource)

## 👤 Author

**Abolfazl Ghorbani** — Software Engineer · Flutter × Rust

[![Website](https://img.shields.io/badge/🌐_Website-abolfazlghorbani84.ir-blue)](https://abolfazlghorbani84.ir)
[![YouTube](https://img.shields.io/badge/▶️_YouTube-@abolfazl_ghorbani-red?logo=youtube)](https://youtube.com/@abolfazl_ghorbani)
[![Email](https://img.shields.io/badge/📧_Email-abolfazlghorbani369@proton.me-purple)](mailto:abolfazlghorbani369@proton.me)
[![GitHub](https://img.shields.io/badge/🐙_GitHub-@aghorbani84-black?logo=github)](https://github.com/aghorbani84)

---

<p align="center">
  ⭐ If AreadmeForge saved you 30 minutes, drop a star — it fuels the roadmap.
</p>

<p align="center">
  Made with ☕ and an unhealthy amount of CSS by <b>Abolfazl Ghorbani</b><br/>
  © 2026 — Released under the MIT License
</p>
