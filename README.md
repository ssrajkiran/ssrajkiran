# Rajkiran Somasundaram — Portfolio

A single-page, dark-glassmorphism portfolio site built with plain HTML/CSS/JS — no framework, no build step. Showcases experience, key projects, technical skills and education for a full-stack software developer role.

**Live site:** [rajkiransomasundaram.dev](https://rajkiransomasundaram.dev) <!-- update once hosted -->

---

## ✨ Features

- Single self-contained `index.html` — fonts, styles and script all in one file, no dependencies to install
- Responsive layout (mobile → desktop), fluid typography with `clamp()`
- Scroll-triggered fade-in animations via `IntersectionObserver`
- Sticky glass-pill navigation with anchor links
- SEO-ready: meta description/keywords, Open Graph + Twitter Card tags, and `Person` JSON-LD structured data for rich search results
- Sections: About, Experience, Key Projects, Technical Skills, Core Strengths, Education & Certifications, Contact

## 🛠️ Tech Stack

- **HTML5 / CSS3** — custom properties, CSS Grid & Flexbox, backdrop-filter glass effects
- **Vanilla JavaScript** — IntersectionObserver for scroll animations
- **Fonts** — [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

## 📁 Project Structure

```
.
├── index.html      # entire site — markup, styles, and script
└── README.md
```

## 🚀 Running Locally

No build tools required — it's a static HTML file.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open index.html        # macOS
# or just double-click index.html / drag it into a browser
```

For live-reload while editing, you can optionally serve it:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## 🌐 Deployment

This is a static site, so it can be deployed for free on any of the following:

- **GitHub Pages** — Settings → Pages → set source to `main` branch / root
- **Vercel** — `vercel deploy`
- **Netlify** — drag-and-drop the folder onto [app.netlify.com/drop](https://app.netlify.com/drop)

After deploying, update the `canonical`, `og:url`, and JSON-LD `url` fields in `index.html` to match your live domain, then submit the URL to [Google Search Console](https://search.google.com/search-console) for indexing.

## 📬 Contact

- **Email:** [ssrajkiran1@gmail.com](mailto:ssrajkiran1@gmail.com)
- **Phone:** +91 70924 28372
- **Location:** Chennai, India

---

© 2026 Rajkiran Somasundaram
