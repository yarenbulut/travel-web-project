# ✈️ Travel Site

A fully responsive, multi‑page travel landing website showcasing dream destinations, luxury hotels and travel tips.

Built with **HTML5**, **Bootstrap 5**, **CSS3**, and **Font Awesome 6**.

---

## 🌐 Live Demo

> Open `index.html` in any modern browser **or** launch a local dev server (e.g. *VS Code → Live Server*) for hot‑reload development.

---


## 📄 Pages & Key Features
| Route | File | Highlights |
|-------|------|------------|
| `/` | `index.html` | Hero **carousel**, global teaser about Travel |
| `/discover` | `discover.html` | Explains coupon‑based travel idea with imagery |
| `/place` | `place.html` | Card grid of three scenic beach destinations |
| `/hotels` | `hotels.html` | Luxury hotel cards, **Book Now** CTA |
| `/contact` | `contact.html` | Bootstrap contact form (name, email, message) |

🔑 **Shared UI**
* Sticky **navbar** with off‑canvas menu (mobile friendly)
* Page‑specific **hero** sections with full‑bleed background images & social icons
* Consistent **footer** & theme colour `#155724`

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Structure | HTML5, semantic tags |
| Styling & Layout | Bootstrap 5.3, CSS3 (`style.css`) |
| Icons | Font Awesome 6 |
| Responsiveness | Bootstrap grid, flex utilities, off‑canvas |

---

## 📂 Project Structure
```
travel-site/
├── index.html
├── discover.html
├── place.html
├── hotels.html
├── contact.html
├── style.css
└── images/
    ├── Travel.png   # logo
    ├── slider.png   # default hero background
    └── ...          # rest of assets
```
> **Tip:** keep all new images inside `images/` and reference them with relative paths for portability.

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/<your‑username>/travel-site.git
cd travel-site
```

### 2. (Optional) Install Live Server
*VS Code* → Extensions → search **Live Server** → *Install*

### 3. Launch
* Double‑click `index.html`, **or**
* Right‑click → *Open with Live Server* to auto‑reload on save.

---

## 🎨 Customisation Guide
| Want to change… | Where |
|-----------------|-------|
| Theme colour | `style.css` → `.navbar-custom`, `.footer-custom`, `.newsletter-container` |
| Hero background | `style.css` → `.hero-section.hero-*` classes |
| Carousel images | `index.html` → `<img src="images/...">` inside `.carousel-item` |
| Navbar links | Any `*.html` → `<nav>` section |
| Text content | Edit the respective HTML file |

---

## 🙌 Contributing
1. **Fork** the repo
2. **Create** your feature branch (`git checkout -b feature/topic`)
3. **Commit** your changes (`git commit -m 'Add cool feature'`)
4. **Push** to the branch (`git push origin feature/topic`)
5. **Open** a pull request

---

## 📜 License
This project is open‑source under the MIT License – feel free to build upon it.

---

Happy travels! 🌍
