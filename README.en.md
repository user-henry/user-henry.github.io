**English** | [简体中文](README.md)

# huangzhiyuan · Personal Portfolio

> The personal portfolio of huangzhiyuan (GitHub: user-henry): selected work, about, skills and contact.

Live: **<https://user-henry.github.io/>**

## What's here

- **Selected work**: NFLSHC Chat, HZYAI, ScreenTool, Clipboard Queue, Fossil Information Manager, Web macOS, Web Linux and OrbitLive — 8 projects in total
- **About / Skills / Contact**
- Responsive layout, scroll animations and project category filtering
- The contact form **stores drafts only in your browser** and never sends anything to a server

## Technical notes

- Built with TanStack Start (React 19 + Vite + Tailwind CSS 4) and exported as a static site for GitHub Pages
- Asset paths match the deployment path used here: `https://user-henry.github.io/`
- `.nojekyll` disables Jekyll so underscore-prefixed directories such as `__grok` are published

## Local preview

```bash
python -m http.server 8080
# open http://127.0.0.1:8080/
```

## Structure

```text
index.html              Home page (pre-rendered HTML)
404.html                Not-found page (same as home)
assets/                 JS and CSS
images/                 Project screenshots and avatar
__grok/                 PWA icon
manifest.webmanifest    PWA manifest
.nojekyll               Skip Jekyll processing
```

## Copyright

Page content and project images belong to huangzhiyuan; fonts are provided by Google Fonts (Noto Sans SC / Noto Serif SC, OFL).
