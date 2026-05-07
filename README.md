# Handyman Bexley 🔧

**https://www.handymanbexley.com**

Friendly, reliable local handyman website for Bexley and surrounding areas. Built for maximum SEO performance, AI search visibility, fast load times and easy GitHub deployment.

---

## 📁 Project Structure

```
handymanbexley/
├── index.html            # Main page — all content
├── 404.html              # Custom 404 error page
├── robots.txt            # Search engine & AI crawler rules
├── sitemap.xml           # XML sitemap for Google/Bing
├── manifest.json         # PWA web app manifest
├── .htaccess             # Apache: HTTPS, caching, headers
├── _headers              # Netlify/Cloudflare Pages headers
├── README.md             # This file
└── assets/
    ├── css/
    │   └── style.css     # All styles (separated from HTML)
    ├── js/
    │   └── main.js       # FAQ, scroll, nav, analytics hooks
    └── images/
        ├── og-image.jpg      # Open Graph / social share image (add yours)
        ├── icon-192.png      # PWA icon 192×192 (add yours)
        └── icon-512.png      # PWA icon 512×512 (add yours)
```

---

## 🚀 Deployment

### GitHub Pages
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://yourusername.github.io/handymanbexley`
5. Add your custom domain `handymanbexley.com` in the Pages settings
6. Add a `CNAME` file containing `www.handymanbexley.com`

### Netlify (recommended — free, fast CDN)
1. Push to GitHub
2. Connect repo at [netlify.com](https://netlify.com)
3. Set custom domain to `handymanbexley.com`
4. Netlify reads `_headers` automatically — no extra config needed

### Apache Hosting (e.g. cPanel)
1. Upload all files to `public_html/`
2. `.htaccess` handles HTTPS redirect, caching and security headers automatically

---

## ✏️ Before Going Live — Update These

| File | What to change |
|------|---------------|
| `index.html` | Replace `07440 788 363` with your real phone number |
| `index.html` | Replace `hello@handymanbexley.com` with your real email |
| `sitemap.xml` | Update `<lastmod>` dates when you make changes |
| `assets/images/` | Add real `og-image.jpg` (1200×630px), `icon-192.png`, `icon-512.png` |
| `manifest.json` | Update phone number in shortcuts |
| `index.html` | Add your Google Analytics GA4 tag (see below) |

### Adding Google Analytics (GA4)
Paste this before `</head>` in `index.html`:
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```
Replace `G-XXXXXXXXXX` with your real Measurement ID.

---

## 📈 SEO Features

| Feature | Implementation |
|---------|---------------|
| Semantic HTML5 | `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>` |
| Schema.org JSON-LD | LocalBusiness + FAQPage structured data |
| Open Graph tags | Facebook, LinkedIn previews |
| Twitter Card | Twitter/X share previews |
| Canonical URL | Prevents duplicate content penalties |
| Geo meta tags | Local search signals |
| robots.txt | Crawler rules inc. AI bots |
| XML Sitemap | Submitted to Google Search Console |
| HTTPS redirect | Via .htaccess |
| Browser caching | 1-year cache on assets |
| GZIP compression | Via .htaccess |
| Security headers | CSP, HSTS, X-Frame-Options |
| PWA manifest | Mobile install + shortcuts |

## 🤖 AI SEO (AISEO) Features

| Feature | Purpose |
|---------|---------|
| `GPTBot` allowed in robots.txt | ChatGPT can index the site |
| `PerplexityBot` allowed | Perplexity AI can reference the site |
| `anthropic-ai` allowed | Claude can reference the site |
| FAQ Schema | Answers shown in AI responses |
| LocalBusiness Schema | Business details fed to AI models |
| Clear semantic structure | AI can extract and cite content accurately |
| Authoritative tone | Increases likelihood of AI recommendation |
| NAP consistency | Name, Address, Phone consistent throughout |

---

## 🛠 Local Development

No build step required — pure HTML, CSS and JS.

```bash
# Option 1: Python (built-in)
python3 -m http.server 8000
# Visit http://localhost:8000

# Option 2: Node live-server
npx live-server
```

---

## 📋 Go-Live Checklist

- [ ] Update phone number throughout
- [ ] Update email address throughout
- [ ] Add real `og-image.jpg` (1200×630px)
- [ ] Add `icon-192.png` and `icon-512.png`
- [ ] Add Google Analytics GA4 tag
- [ ] Submit `sitemap.xml` to Google Search Console
- [ ] Submit `sitemap.xml` to Bing Webmaster Tools
- [ ] Set up Google Business Profile at business.google.com
- [ ] Link website to Google Business Profile
- [ ] Verify domain ownership in Search Console
- [ ] Check PageSpeed score at pagespeed.web.dev
- [ ] Test structured data at search.google.com/test/rich-results

---

## 📞 Contact

**Handyman Bexley**
📍 Bexley, London DA5
📞 07440 788 363
✉️ hello@handymanbexley.com
🌐 https://www.handymanbexley.com
