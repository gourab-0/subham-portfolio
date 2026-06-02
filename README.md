# Subham Deysarkar — Portfolio Website

An ultra-premium, fully responsive single-page portfolio website for **Subham Deysarkar**, a Graphic Designer & VFX Artist based in Mumbai, Maharashtra.

Built entirely with **pure HTML5, vanilla CSS, and high-performance JavaScript** — no frameworks, no dependencies.

---

## 🎨 Design System — Dusty Editorial Palette

| Token | Hex | Usage |
|---|---|---|
| `--bg-base` | `#F9F4EE` | Main page background |
| `--bg-surface` | `#EDE4D8` | Section & card backgrounds |
| `--accent-cyan` | `#B07755` | Primary accent (buttons, headings) |
| `--accent-purple` | `#7A4A2E` | Secondary accent |
| `--text-primary` | `#252535` | Body and heading text |
| `--text-muted` | `#C9BAA8` | Captions, labels |

**Typography Stack:**
- *Syne* (800) — Giant editorial hero word, section headings
- *Playfair Display* (900) — Display-size italic accents
- *DM Sans* (400, 500) — High-readability body copy

---

## 🚀 Features

### 📰 Brutalist Editorial Hero Section
Full-viewport hero with a giant gradient two-tone `"portfolio"` title, glassmorphic stats bar, and an interactive WebGL-style particle canvas that responds to mouse movement.

### 🖼️ Full Portfolio Grid — 39 Projects
All images from 5 project categories displayed in a filterable 3-column grid:

| Category | Count |
|---|---|
| Samsung Campaign | 14 |
| Magazine Layouts | 4 |
| Tea Company Cafe Branding | 9 |
| Business Cards | 5 |
| Brochures | 7 |

**Lightbox Modal**: Click any card for full-screen image preview with keyboard `Esc` support.

### 🧰 Tools & Expertise Section
7-tool card grid (Adobe Photoshop, Illustrator, After Effects, Premiere Pro, 3ds Max, CorelDRAW, Canva) with brand-colored icons and animated progress bars. Includes an infinite scrolling text marquee.

### 🖱️ Dual Cursor Follower (Desktop)
Warm-brown primary dot + lagging ring follower with smooth lerp physics. Auto-disabled on mobile.

### 📱 Fully Responsive
- Desktop: 3-column grid, 4-column tools grid, full particle canvas
- Tablet: 2-column grid
- Mobile: Single column, full-screen hamburger menu, no custom cursor

---

## 📂 File Structure

```
shubham portfolio/
├── index.html              # Unified SPA (all CSS & JS inlined)
├── README.md               # This file
├── LICENSE                 # MIT License
├── .gitignore
└── images/
    ├── shubham-1.jpeg      # About section portrait
    ├── Samsung/            # 14 campaign images (design-1, design-11, design-111, ...)
    ├── magzine/            # 4 magazine layout images
    ├── tcc/                # 9 Tea Company Cafe branding images
    ├── Bcard/              # 5 business card designs (1.jpeg – 5.jpeg)
    └── broucher/           # 7 brochure pages (1.jpeg – 7.jpeg)
```

---

## 🛠️ Local Preview

**Option A — Direct Open:**
Double-click `index.html` to open in any modern browser (Chrome, Edge, Firefox, Safari).

**Option B — Local Dev Server (recommended for particles/canvas):**
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🚀 Deployment Checklist

### 1. Formspree Contact Form
Before going live, replace the placeholder form endpoint:
1. Create a free account at [Formspree](https://formspree.io/)
2. Create a new form and copy your Endpoint ID
3. In `index.html`, find and replace `PLACEHOLDER_ID`:
```html
<form action="https://formspree.io/f/YOUR_ENDPOINT_ID" method="POST">
```

### 2. Hosting Options (Free)

| Platform | Steps |
|---|---|
| **Vercel** *(Recommended)* | Link GitHub repo → Click Deploy |
| **GitHub Pages** | Repo Settings → Pages → `main` branch → Save |
| **Netlify** | Drag & drop the project folder on [netlify.com](https://netlify.com) |

---

## 📬 Contact

**Subham Deysarkar**  
Mumbai, Maharashtra  
📧 SubhamDeysarkar15@gmail.com  
📧 subhamdeysarkar146@gmail.com  
📱 +91 93223 27584  
📸 [@shubhhammmm_](https://www.instagram.com/shubhhammmm_)
