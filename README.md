# 🚀 Sreenand Vinod A V — Portfolio Website

> Futuristic Dark AI Theme | Cyberpunk Aesthetic | GitHub Pages Ready

![Preview](assets/images/preview-description.txt)

---

## 🌐 Live Demo

Deploy to GitHub Pages and your site will be live at:
`https://sreenand22-2003.github.io/portfolio/`

---

## 📁 Project Structure

```
sreenand-portfolio/
│
├── index.html              ← Main HTML (all sections)
│
├── css/
│   ├── main.css            ← Core styles, layout, components
│   ├── animations.css      ← Keyframe animations, hover effects
│   └── responsive.css      ← Mobile / tablet / wide responsive rules
│
├── js/
│   ├── particles.js        ← Canvas particle background system
│   ├── animations.js       ← Typing effect, scroll reveals, skill bars
│   └── main.js             ← Navbar, filters, interactions
│
├── assets/
│   ├── images/
│   │   └── profile.jpg     ← ⚠️ REPLACE THIS with your photo
│   └── sreenand_resume.pdf ← ⚠️ REPLACE THIS with your CV
│
└── README.md               ← This file
```

---

## ✏️ HOW TO EDIT CONTENT

### 1. Personal Info (index.html)
Open `index.html` and find these sections to update:

**Name & Title**
```html
<!-- Line ~48 -->
<h1 class="hero-name">SREENAND<br/><span class="name-highlight">VINOD A V</span></h1>
```

**Typed Role Phrases** (js/animations.js, line ~14)
```js
const phrases = [
  'Data Scientist',
  'AI Innovator',
  // Add your own here
];
```

**Description text** — search for `hero-description` in index.html.

**Email, Phone, Location** — search for `contact-info` section in index.html.

---

### 2. Replacing Profile Photo
- Save your photo as `assets/images/profile.jpg`
- Recommended: 400×400px, square, JPG/PNG
- If no photo is set, an animated "SV" initials avatar appears automatically

---

### 3. Resume / CV
- Replace `assets/sreenand_resume.pdf` with your actual PDF
- Keep the filename the same OR update all references in index.html:
  ```html
  href="assets/sreenand_resume.pdf"
  ```

---

### 4. Adding / Editing Projects
In `index.html`, find the `projects-grid` section. Copy this block and edit:

```html
<div class="project-card" data-category="ml" data-aos="fade-up">
  <div class="card-glow"></div>
  <div class="card-header">
    <div class="card-icon">⬡</div>
    <div class="card-links">
      <a href="YOUR_GITHUB_URL" target="_blank" class="card-link">GH</a>
      <a href="YOUR_LIVE_URL" target="_blank" class="card-link">↗</a>
    </div>
  </div>
  <h3 class="card-title">Project Name</h3>
  <p class="card-desc">Short project description here.</p>
  <div class="card-stack">
    <span class="stack-tag">Python</span>
    <span class="stack-tag">Scikit-learn</span>
  </div>
  <div class="card-footer">
    <span class="card-category">MACHINE LEARNING</span>
    <span class="card-year">2025</span>
  </div>
</div>
```

**Filter categories**: `data-category` can be `ml`, `nlp`, `eda`, or `app`.

---

### 5. Updating Social Links
Search for these in `index.html` and replace with your actual URLs:
- `https://github.com/sreenand22-2003`
- `https://linkedin.com/in/sreenand-vinod`
- `mailto:sreenandmzhd@gmail.com`
- `tel:+917994876760`

---

### 6. Blog Posts
In `index.html`, find the `blog-grid` section. Edit each `blog-card` with:
- Your article title
- Short preview text
- A link to your actual post (Medium, Dev.to, Hashnode, etc.)

---

### 7. Skills & Progress Bars
In `index.html`, find the `skills-grid` section:
```html
<div class="skill-bar-item">
  <div class="skill-label"><span>Python</span><span class="skill-pct">90%</span></div>
  <div class="skill-track"><div class="skill-fill" data-width="90"></div></div>
</div>
```
Change `90` in both `skill-pct` text and `data-width` to your actual skill level.

---

### 8. Colors / Theme (css/main.css)
All colors are CSS variables at the top of `main.css`:
```css
:root {
  --cyan: #00f5ff;    /* Primary accent */
  --purple: #a855f7;  /* Secondary accent */
  --blue: #3b82f6;    /* Tertiary */
  --bg-primary: #030712;  /* Main background */
}
```
Change `--cyan` to any color to instantly retheme the entire site.

---

## 🚀 DEPLOYING TO GITHUB PAGES

### Method 1: Simple Upload
1. Create a new repository on GitHub (e.g., `portfolio`)
2. Upload all files from this folder
3. Go to **Settings → Pages**
4. Set source to **Deploy from branch → main → / (root)**
5. Click Save — your site is live in ~2 minutes!

### Method 2: Git CLI
```bash
cd sreenand-portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/sreenand22-2003/portfolio.git
git push -u origin main
```
Then enable GitHub Pages in repository Settings.

### Custom Domain (Optional)
1. Create a file named `CNAME` in the root folder
2. Add your domain: `www.sreenand.dev`
3. Configure DNS at your domain provider

---

## 🔧 Local Development

No build tools needed! Just open `index.html` in a browser.

For best results, use a local server:
```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# VS Code
Install "Live Server" extension → Right-click index.html → Open with Live Server
```

---

## 📦 DEPENDENCIES

All loaded via CDN — no npm install needed:
- **Orbitron** font — Google Fonts
- **Rajdhani** font — Google Fonts  
- **Share Tech Mono** font — Google Fonts

No external JavaScript libraries required. Everything is vanilla JS.

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| IE 11 | ❌ Not supported |

---

## 📄 License

Free to use for personal portfolio. Please don't redistribute as a template without attribution.

---

**Built with ❤️ by Sreenand Vinod A V**  
📧 sreenandmzhd@gmail.com | 🐙 github.com/sreenand22-2003
