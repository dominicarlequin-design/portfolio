# 👋 Dominic Arlequin — Portfolio

Personal portfolio site. Black-and-white editorial design, built as static pages with a lightweight custom templating system instead of a framework.

🔗 **Live:** https://dominicarlequin-design.github.io/portfolio/

---

## 🛠️ Stack

- Static HTML/CSS/JS, no build framework
- Custom `x-dc` templating (`support.js`, compiled from a `dc-runtime` source) for shared components across pages
- `image-slot.js` for fillable image placeholders
- Google Fonts: Instrument Serif (headings), DM Sans (body)
- Deployed via GitHub Pages and Vercel

## 📁 Structure

| File | Purpose |
|---|---|
| `index.html` | Homepage |
| `Nav.dc.html` | Shared nav component |
| `Background.dc.html` | Shared background/layout component |
| `Projects.dc.html` | Projects page |
| `What I Bring.dc.html` | About/skills page |
| `Contact.dc.html` | Contact page |
| `support.js` | Templating runtime (generated, don't edit directly) |
| `image-slot.js` | Fillable image placeholder component |
| `favicon.svg` | Site favicon |
| `uploads/` | Screenshots, in-progress assets |

## ⚙️ Local Dev

Open `index.html` with a local server (e.g. VS Code Live Server). No build step required for static pages.

## 📝 Notes

`.dc.html` files are component templates rendered by `support.js`, not standalone pages. If `support.js` needs changes, edit the `dc-runtime` TypeScript source and rebuild rather than hand-editing the generated file.
