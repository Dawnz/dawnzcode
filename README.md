# dawnzcode.com — Personal Website

> **Damian Green** · Software Developer · Founder of Dawnz Apps & Services

Live at: [dawnzcode.com](https://dawnzcode.com)

---

## About

Personal biography and portfolio website for Damian Green — Full-Stack Software Developer, AWS Certified Engineer, and founder of Dawnz Apps & Services. Built with a cyber-matrix aesthetic using vanilla HTML, CSS, and JavaScript.

---

## Projects Showcased

| Project | URL | Status |
|---|---|---|
| KPoppin | [kpoppin.dawnzcode.com](https://kpoppin.dawnzcode.com) | ● Live |
| Jamaica Classifieds | [jamaica-classifieds.dawnzcode.com](https://jamaica-classifieds.dawnzcode.com) | ● Live |
| Dawnz Enterprise API | api.dawnzcode.com | ◌ Expanding |
| Dawnz Mobile | mobile.dawnzcode.com | ◎ Building |
| Dawnz Analytics | analytics.dawnzcode.com | ◌ Expanding |
| IT Consultancy Portal | consult.dawnzcode.com | ◎ Planned |

---

## Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **Fonts:** Cinzel, Share Tech Mono, Raleway (Google Fonts)
- **Hosting:** Vercel
- **Domain:** dawnzcode.com

---

## Folder Structure

```
dawnzcode/
├── index.html                  # Main biography/portfolio page
├── vercel.json                 # Vercel deployment config
├── .gitignore
├── README.md
│
├── public/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── dawnz_logo.png          # Static logo (1360x960)
│   │   │   ├── dawnz_logo_animated.html # Animated logo page
│   │   │   └── dawnz_desktop.gif        # Desktop wallpaper (1920x1080)
│   │   ├── fonts/                       # Self-hosted fonts (if needed)
│   │   └── icons/                       # Favicons and app icons
│   ├── css/
│   │   └── (future: extracted stylesheets)
│   └── js/
│       └── (future: extracted scripts)
│
├── pages/
│   └── (future: additional pages e.g. blog, projects detail)
│
└── .github/
    └── workflows/
        └── deploy.yml          # GitHub Actions CI/CD (optional)
```

---

## Deploying to Vercel

### Option 1 — Vercel Dashboard (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Vercel auto-detects static site — click **Deploy**
5. Add your custom domain `dawnzcode.com` in **Settings → Domains**

### Option 2 — Vercel CLI
```bash
npm install -g vercel
vercel login
vercel --prod
```

---

## Custom Domain Setup

In your domain registrar (e.g. Namecheap, GoDaddy), add these DNS records:

| Type | Name | Value |
|---|---|---|
| A | @ | 76.76.21.21 |
| CNAME | www | cname.vercel-dns.com |

For subdomains (KPoppin, Jamaica Classifieds, etc.), add:

| Type | Name | Value |
|---|---|---|
| CNAME | kpoppin | cname.vercel-dns.com |
| CNAME | jamaica-classifieds | cname.vercel-dns.com |

---

## License

© 2025 Damian Green · Dawnz Apps & Services · All rights reserved.
