# Shubham Deysarkar — Portfolio Website

An ultra-premium, highly interactive, and responsive single-page portfolio website designed and built for **Shubham Deysarkar**, a professional Graphic Designer & VFX Artist based in Mumbai, Maharashtra. 

The website is engineered using a custom brutalist magazine cover layout, combining pure HTML5, vanilla CSS, and high-performance JavaScript to establish a world-class commercial aesthetic.

---

## 🎨 Design System Specifications (Locked)

*   **Main Background**: Deep Obsidian (`#07070D`)
*   **Section Backgrounds (Alternating)**: 
    *   Hero Section: `#07070D`
    *   Projects Grid Section: `#0D0D14`
    *   Toolkit Section: `#07070D`
    *   Contact Section: `#0D0D14`
    *   Footer Section: `#07070D`
*   **Card Backgrounds**: Dark Slate (`#16161F`)
*   **Accents**: Tech-Cyan (`#00E5FF`) and Electric Purple (`#9D4EDD`)
*   **Typography**: 
    *   *Playfair Display* (900 Italic) — Giant brutalist masked title
    *   *Syne* (700, 800) — Bold, architectural headings
    *   *DM Sans* (400, 500) — Elegant, high-readability body copy
*   **Custom Scrollbar**: Customized glowing cyan scrollbars configured via CSS webkit selectors.

---

## 🚀 Key Interactive & Visual Features

### 📰 Brutalist Editorial Hero Section
An asymmetric layout featuring a giant, full-width masked title `"portfolio"` written in outline styling. It is overlaid with a solid cyan filled version clipped dynamically (`clip-path`) for a sophisticated cover-page feel. Pinned at the bottom is a glassmorphic stats panel displaying his commercial credentials.

### 🖼️ Real-World Campaign Showcases (14 Project Items)
*   **Samsung Brand Campaigns**: Displays the subway billboard mockup, shopping mall hanging banner, airport directory, and multi-screen device grids, alongside the three original high-resolution S25 campaign posters.
*   **Tea Company Cafe Branding**: Focuses on a rustic-modern layout displaying the cafe's circular crimson logo, detailed print/digital food and beverage menus, the Combo Offers flyer, and the "We're Open" launch banner.
*   **3D Mouse Parallax Tilt**: Card layers rotate dynamically in 3D perspective relative to cursor coordinates on desktop (capped at ±8 degrees to maintain professional luxury).
*   **Lightbox Modal**: Click cards to view high-resolution mockups inside a full-screen blurred lightbox modal supporting backdrop dismissals, close triggers, and keyboard `Esc` exit hooks.

### ⚡ Redesigned Toolkit Section
*   **Software Cards**: Adobe Photoshop, Illustrator, After Effects, Premiere Pro, and Blender visual cards decorated in custom brand colors with горизонтальные CSS progress fill-bars.
*   **Vector Specialities**: Handsomely detailed specialty cards integrated with customized, inline SVG vector graphic icons (no basic text listings).
*   **Infinity Scrolling Marquee**: Seamless horizontal infinite loop ticking software names.

### 🖱️ Advanced Dual Cursor Follower
*   A tech-cyan primary dot cursor (`#cursor`) and a larger secondary lag-follower ring (`#cursor-follower`) tracking the pointer with smooth lerp physics. Hovering over active buttons or cards dynamically expands the pointer size.
*   *Note: Automatically deactivated on mobile viewports to conserve device batteries and performance.*

---

## 📂 File Structure

```
Shubham-portfolio/
├── index.html            # Core unified SPA (All styling & JS inlined)
├── README.md             # Project documentation and handbook
├── LICENSE               # Open-source MIT License
├── .gitignore            # Git exclusion guidelines
└── images/               # Standardised campaign and layout assets
    ├── image-1.jpeg      # Samsung S25 Ultra Poster
    ├── image-2.jpeg      # Samsung Printed Desk Mockups
    ├── image-3.jpeg      # Samsung Devices concrete arrangement
    ├── samsung-subway.jpg
    ├── samsung-mall.jpg
    ├── samsung-airport.jpg
    ├── samsung-devices.jpg
    ├── samsung-zfold.jpg
    ├── tcc-logo.jpg
    ├── tcc-menu1.jpg
    ├── tcc-menu2.jpg
    ├── tcc-opening.jpg
    ├── tcc-combo.jpg
    ├── tcc-open.jpg       # Tea Company "We're Open" launch banner
    ├── proof-1.jpeg       # Instagram feed live proof
    ├── proof-2.jpeg       # Physical tabletop menu stand print proof
    └── proof-3.jpeg       # Google Maps storefront signage proof
```

---

## 🛠️ Local Development & Preview

To preview the website locally on your computer:
1. **Option A (Instant Open)**: Double-click the `index.html` file to launch it directly in any modern browser (Chrome, Edge, Safari, Firefox).
2. **Option B (Local Dev Server)**: 
   If you have Python installed, you can launch a local HTTP server by executing this terminal command inside the project root:
   ```bash
   python -m http.server 8000
   ```
   Then open your browser and navigate to `http://localhost:8000`.

---

## 🚀 Final Deployment Checklist for Shubham

### 1. Formspree Integration
Shubham must configure the email contact form before deploying:
1. Sign up for a free account at [Formspree](https://formspree.io/).
2. Create a new form and copy the Form Endpoint ID.
3. Open `index.html` and replace `PLACEHOLDER_ID` on **line 1622** with the endpoint ID:
   ```html
   <form action="https://formspree.io/f/YOUR_ENDPOINT_ID" method="POST" id="contact-form">
   ```

### 2. Static Web Hosting (Free & Instant)
Since the portfolio is a lightweight, single-page client site, Shubham can deploy it in under two minutes:
*   **Vercel (Recommended)**: Create a free account at [Vercel](https://vercel.com/), link this GitHub repository, and click **Deploy**. Vercel handles all asset hostings and SSL setups automatically.
*   **GitHub Pages**: Go to the GitHub repository settings ➔ Pages tab ➔ Select the `main` branch as the build source, and click Save.
