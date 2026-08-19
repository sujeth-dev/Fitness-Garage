# Fitness Garage — Official Website

**Kanaka Nagar, Horamavu · Bangalore 560036**
4.9★ · 623 Google Reviews

---

## Project Structure

```
fitness-garage/
├── index.html                  ← Single-page website (all sections)
├── robots.txt                  ← Bot crawl directives
├── sitemap.xml                 ← Update <loc> URL with your domain before deploy
├── css/
│   ├── globals.css             ← Design tokens, reset, fonts, ticker animation
│   ├── navbar.css              ← Sticky navbar + mobile drawer
│   ├── hero.css                ← Full-screen hero section + background image
│   ├── sections.css            ← About, Programs, Membership, Gallery,
│   │                              Facilities, Reviews, Contact
│   └── footer.css              ← Footer + floating WhatsApp button
├── js/
│   └── main.js                 ← Nav toggle, scroll reveal, counters, smooth scroll
└── images/
    ├── logo1.png               ← Gym logo (navbar + footer + favicon)
    ├── 1.jpg / 1.webp          ← Hero background + gallery (Main Floor)
    ├── 2.jpg / 2.webp          ← About section + gallery (Equipment Zone)
    ├── 4.jpg / 4.webp          ← Gallery (Training Area)
    ├── 5.jpg / 5.webp          ← Gallery (Free Weights)
    ├── 6.jpg / 6.webp          ← Gallery (Strength Zone)
    ├── 7.jpg / 7.webp          ← Gallery (Powerlifting)
    ├── cardio.jpg / .webp      ← Gallery (Cardio Zone)
    ├── group-classes1.jpg/.webp← Gallery (Group Classes)
    ├── personal1.jpg / .webp   ← Gallery (Personal Training)
    └── world-class.jpg / .webp ← Facilities section
```

> Every image has a `.webp` companion. The site automatically serves WebP to
> browsers that support it (Chrome, Firefox, Edge, Safari 14+) and falls back
> to JPEG for older browsers — no manual action needed.

---

## Run Locally

Open `index.html` directly in any browser, or use a local server for full feature parity:

```bash
# Python
python -m http.server 3000

# Node.js
npx serve .

# VS Code — install "Live Server" → right-click index.html → Open with Live Server
```

---

## Deploy

### GitHub Pages
```bash
git add .
git commit -m "deploy"
git push origin main
```
Repo → **Settings → Pages → Branch: main → / (root) → Save**

Live at: `https://thedenn0007-afk.github.io/Fitness-Garage/`

### Netlify (drag & drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `fitness-garage/` folder onto the page
3. Done — live URL is generated instantly

### After deploying
Update the placeholder URLs in these two files with your actual domain:
- `sitemap.xml` — `<loc>` and `lastmod`
- `robots.txt` — `Sitemap:` line
- `index.html` — `og:image` meta tag (line ~17) — needs an absolute URL to work on social shares

---

## Quick Customisations

| What to change | Where |
|---|---|
| Logo | Replace `images/logo1.png` |
| WhatsApp number | Search `918951544738` in `index.html`, replace all occurrences |
| Phone numbers | `#contact` section + footer in `index.html` |
| Email | `#contact` section + footer in `index.html` |
| Pricing | `#membership` section in `index.html` |
| Opening hours | `#contact` section in `index.html` |
| Address | `#contact` section + footer in `index.html` |
| Programs | `#programs` section in `index.html` |
| Colour scheme | `css/globals.css` — edit the `:root` CSS variables |
| Hero background | Replace `images/1.jpg` (and regenerate `images/1.webp`) |

---

## Contact Details

| | |
|---|---|
| Phone | +91 89515 44738 |
| Phone | +91 63645 69090 |
| Phone | +91 63640 01718 |
| WhatsApp | +91 89515 44738 |
| Email | Fitnessgarage23@gmail.com |
| Instagram | [@fitness_garage2023](https://www.instagram.com/fitness_garage2023) |
| Address | Kanaka Nagar, Horamavu, Kalkere, Bangalore, Karnataka 560036 |
