# PROFITILO

[![Demo](https://img.shields.io/badge/demo-marinesprofile.vercel.app-blue?logo=vercel&logoColor=white)](https://marinesprofile.vercel.app)  [![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)  [![Last commit](https://img.shields.io/github/last-commit/noxarix/PROFITILO)](https://github.com/noxarix/PROFITILO/commits)  [![Repo size](https://img.shields.io/github/repo-size/noxarix/PROFITILO)](https://github.com/noxarix/PROFITILO)

<p align="center">
  <img src="assets/hero.png" alt="PROFITILO hero" width="900" style="border-radius:12px;box-shadow:0 10px 30px rgba(0,0,0,0.35)"/>
</p>

---

A modern, stylish personal portfolio to showcase skills, projects, achievements, and the journey of an aspiring student developer.

Quick links: [Website](https://marinesprofile.vercel.app) • [Repository](https://github.com/noxarix/PROFITILO)

## ✨ Highlights

- Clean, responsive single-page design with About, Projects, Skills and Contact
- Lightweight and fast — ideal for static-hosting (Vercel, Netlify, GitHub Pages)
- Student-focused with a bold, modern look

## 🎨 "ᴄʜᴀᴛ" font-style & hero

I added a stylish display option for the heading using the fancy characters **ᴄʜᴀᴛ** (Unicode small-caps style). To get a polished look, include this CSS snippet in your stylesheet (e.g. `css/style.css`) and replace the hero image at `assets/hero.png` with the screenshot you uploaded.

```css
/* Fancy "ᴄʜᴀᴛ" heading style */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap');

:root{
  --accent: #b85b5b; /* warm red accent to match the hero */
  --bg: #000;
  --muted: #cfcfcf;
}

body{font-family: 'Poppins', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; background:var(--bg); color:#fff}
.hero-title{font-weight:800; font-size:clamp(2rem,4vw,3.5rem); letter-spacing:0.02em}
.hero-subtitle{font-weight:600; color:var(--accent)}

/* special frame for the CHAT-styled word */
.chat-badge{
  display:inline-block;
  font-variant:small-caps; /* fallback */
  color:var(--accent);
  text-shadow: 0 6px 18px rgba(184,91,91,0.25);
  font-family: 'Poppins', sans-serif;
  padding:0 0.25rem;
  border-radius:6px;
}

/* rounded hero image frame */
.hero-image{width:100%; max-width:900px; border-radius:50%; box-shadow: 0 20px 60px rgba(184,91,91,0.12); border:8px solid rgba(184,91,91,0.06)}

/* button */
.btn-primary{background:var(--accent); color:#fff; padding:0.85rem 1.4rem; border-radius:10px; border:none; font-weight:700}
```

And a small HTML snippet to use in `index.html`:

```html
<section class="hero" style="display:flex;align-items:center;gap:2rem;">
  <img src="assets/hero.png" alt="Marine — hero" class="hero-image" />
  <div>
    <p class="hero-subtitle">Hey I'm <strong>Marine</strong></p>
    <h1 class="hero-title">I'm a <span class="chat-badge">ᴄʜᴀᴛ</span> <span class="hero-accent">STUDENT</span></h1>
    <p style="color:var(--muted);max-width:520px">I'm an aspiring student developer passionate about turning ideas into reality. I enjoy exploring new technologies, solving problems, and creating tools that make learning and connecting easier.</p>
    <div style="margin-top:1.2rem">
      <a class="btn-primary" href="#about">About Me</a>
    </div>
  </div>
</section>
```

This produces a bold headline where the word ᴄʜᴀᴛ is highlighted with the accent color and a subtle glow — matching the dark/red theme in your screenshot.

## 🖼 Screenshots

The README references `assets/hero.png` — I can commit the image you provided and save it as `assets/hero.png` so the README shows correctly. If you'd like me to add optimized WebP versions I can do that too.

## 🔗 Connect with me

<p align="center">
  <a href="mailto:mrchikoo31@gmail.com"><img src="https://img.shields.io/badge/Email-mrchikoo31@gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://x.com/nox_shadowx" style="margin-left:8px"><img src="https://img.shields.io/badge/X-@nox_shadowx-1DA1F2?logo=twitter&logoColor=white" alt="X / Twitter"></a>
  <a href="https://instagram.com/_nox_shadowx" style="margin-left:8px"><img src="https://img.shields.io/badge/Instagram-@_nox_shadowx-E1306C?logo=instagram&logoColor=white" alt="Instagram"></a>
  <a href="https://t.me/nox_shadowx" style="margin-left:8px"><img src="https://img.shields.io/badge/Telegram-@nox_shadowx-26A5E4?logo=telegram&logoColor=white" alt="Telegram"></a>
</p>

*(All usernames provided by the repository owner.)*

## 🤝 License

This repository is licensed under the MIT License — see the `LICENSE` file for details.

## 📦 Local development

1. Clone:

   git clone https://github.com/noxarix/PROFITILO.git
2. Serve:

   python -m http.server 3000

3. Open http://localhost:3000

---

If you want, I will now:
- (A) Commit the image you attached as `assets/hero.png` and also create `assets/screenshot-1.png` from the same image (recommended), or
- (B) Wait for you to upload different images / provide exact files.

Reply with “A” to let me commit the image now, or “B” to upload later.