# 🚀 Saksham Thakur — Developer Portfolio

A fully custom, single-file cyberpunk-themed developer portfolio with zero dependencies.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-00f5ff?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML-Single%20File-ff006e?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-00f5ff?style=for-the-badge)

---

## ✨ Features

- **Glitch animation** on hero name with cyan & magenta tear effect
- **Animated particle field** with grid background and connection lines
- **Custom cursor** with lagging ring that reacts to hover
- **3D card tilt** on project cards following mouse position
- **Scanning line** effect sweeping the page
- **Counter animations** on stats (CGPA, team size, events)
- **Dark / Light mode toggle** with localStorage persistence
- **Hamburger menu** with slide-in drawer for mobile
- **Resume download** — actual PDF embedded directly in the file
- **Zero external dependencies** — one `.html` file, works offline

---

## 🛠 Tech Stack

| Layer | Choice |
|-------|--------|
| Structure | Vanilla HTML5 |
| Styling | Vanilla CSS3 (animations, clip-path, CSS variables) |
| Logic | Vanilla JavaScript (ES6) |
| Fonts | Google Fonts — Orbitron + Space Mono |
| Canvas | HTML5 Canvas API (particle system) |

---

## 📁 Project Structure

```
portfolio.html    ← entire portfolio (HTML + CSS + JS + embedded PDF)
README.md         ← this file
```

That's it. One file.

---

## 🚀 Deployment

### Netlify Drop (30 seconds, no account needed)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag and drop `portfolio.html`
3. Get a live URL instantly — rename to `saksham-portfolio.netlify.app`

### GitHub Pages (free, permanent)
1. Create a new GitHub repo
2. Upload `portfolio.html` and rename it to `index.html`
3. Go to **Settings → Pages → Source → main branch**
4. Live at `yourusername.github.io/repo-name` in ~2 mins

### Vercel (best for custom domain)
1. Push to a GitHub repo
2. Import at [vercel.com](https://vercel.com)
3. Auto-deploys on every push

---

## 🎨 Customization

All content is in plain HTML — just open `portfolio.html` in any editor.

| What to change | Where to find it |
|----------------|-----------------|
| Name, title, bio | `#hero` section |
| Stats (CGPA, team size) | `.hero-stats` div |
| Work experience | `#experience` section |
| Projects | `#projects` section |
| Skills | `#skills` section |
| Contact links | `#contact` section + mobile drawer |
| Resume PDF | Replace the base64 string in `RESUME_B64` variable |
| Color scheme | `:root` CSS variables (`--cyan`, `--magenta`, `--bg`) |

### Updating the resume PDF
1. Convert your new PDF to base64:
   ```bash
   base64 -i your_resume.pdf | tr -d '\n'
   ```
2. Find `var RESUME_B64 = '...'` in the `<script>` section
3. Replace the long string with your new base64 output

---

## 📱 Browser Support

| Browser | Status |
|---------|--------|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Edge 90+ | ✅ Full support |
| Mobile Chrome | ✅ Full support |
| Mobile Safari | ✅ Full support |

---

## 👤 About

**Saksham Thakur**
- 🎓 B.Tech CSE @ VIT Vellore (2023–2027) — CGPA 8.7/10
- 💼 Ex Full Stack Intern & Team Lead @ UptoSkills
- 🎨 Design Head, IET Student Chapter VIT
- 📍 New Delhi, India

**Links:**
- GitHub: [github.com/Saksham6349](https://github.com/Saksham6349)
- LinkedIn: [linkedin.com/in/saksham-thakur-892936261](https://linkedin.com/in/saksham-thakur-892936261)
- Email: saksham3749@gmail.com

---

## 📄 License

MIT — feel free to use this as a template for your own portfolio.
