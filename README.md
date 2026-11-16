# Yonas Birhanu — Portfolio

A personal portfolio website for **Yonas Birhanu**, Digital Creative based in Addis Ababa, Ethiopia. Brand design, campaigns, and cinematic AI video — presented in a dark, animated, single-page site.

**Live demo:** _add your GitHub Pages / Netlify / Vercel URL here_

![Portfolio preview](preview.png)

---

## ✨ Features

- **Single file, zero build** — everything (HTML, CSS, JS, fonts links, profile photo) lives in `index.html`. No npm, no bundler, deploy anywhere.
- **5 languages** with a live switcher — English, አማርኛ (Amharic), العربية (Arabic, full right-to-left), Français, Italiano. Choice is saved between visits.
- **3 themes** — Gold (charcoal + yellow), Dark (monochrome), White (light). Also saved between visits.
- **Animated throughout** — page loader, custom cursor, kinetic hero, marquee, scroll reveals, animated counters and skill bars.
- **Filterable work gallery** with a lightbox, an AI-tools grid, and an AI-videos section with a modal.
- **Responsive** down to phone width, with a mobile menu.
- **Accessible** — honors `prefers-reduced-motion`, keyboard-navigable, semantic markup.
- **Click-to-copy** phone and email, plus a `tel:` link.

## 🧰 Built with

- Semantic HTML5
- Modern CSS (custom properties, grid, `color-mix`, container-friendly layout)
- Vanilla JavaScript — no frameworks, no dependencies
- Google Fonts: Space Grotesk, Inter, JetBrains Mono, Noto Sans Ethiopic, Noto Sans Arabic

## 🚀 Deploy on GitHub Pages

1. Create a new repository (e.g. `yonas-birhanu-portfolio`).
2. Add `index.html` (and this `README.md`) and commit:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment**, set **Source** to `Deploy from a branch`, branch `main` / `root`, then **Save**.
4. Your site goes live at `https://<your-username>.github.io/<your-repo>/` within a minute or two.

> Tip: to use a custom domain, add it under **Settings → Pages → Custom domain** and create a `CNAME` DNS record at your registrar.

## ✏️ Editing your content

All text and data sit near the bottom of `index.html`, in two clearly-marked objects:

- **`CONFIG`** — the things that don't translate: name, phone, email, LinkedIn, the project/video accent colors, tool names, and dates.
- **`T`** — every translatable string, one block per language (`en`, `am`, `ar`, `fr`, `it`). Edit the matching block for each language you want to change.

> **Note:** the experience entries, project names, and descriptions are realistic **placeholders**, not final career data. Replace them in `CONFIG` and `T` with your real work.

To swap the profile photo, replace the `data:image/jpeg;base64,...` string on the hero `<img>` inside `.avatar`.

## 📁 Structure

```
.
├── index.html     # the entire site
└── README.md      # this file
```

## 📄 License

© 2026 Yonas Birhanu. All rights reserved.

---

Made by [Walia Digital Solution](https://waliadigitalsolution.com/)
