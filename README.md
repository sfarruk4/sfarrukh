# Saleh Farrukh — Personal Website

A fast, responsive, single-page portfolio — no build step, no frameworks. Pure
HTML, CSS, and a little vanilla JavaScript, so it drops straight into GitHub and
deploys free on GitHub Pages.

**Live at:** https://sfarruk4.github.io/sfarrukh/ (after you enable Pages — see below)

---

## Still-to-personalize checklist

Most of the site already uses your real details. A few things are left for you:

- [ ] **Buy Me a Coffee:** create an account, then replace `YOUR-USERNAME` in the
      coffee link inside `index.html`. (Payment details stay private — see below.)
- [ ] **Cover letter:** replace `assets/docs/cover-letter.pdf` with your real one
      (or delete the section if you don't want it).
- [ ] **Art gallery dates:** the entry says "Add dates" — fill in the real ones in `index.html`.
- [ ] **Project links:** GeoCraft / AirManage cards say "Add repo link" — point them at your repos.
- [ ] **Photos:** replace the `.svg` placeholders in `assets/img/` with your own images.
- [ ] **Link-preview image (optional):** add a 1200×630 `assets/img/og-cover.jpg`
      so a nice image shows when you share the link on LinkedIn / WhatsApp.

## Buy Me a Coffee — payments stay private

The support button links to buymeacoffee.com. That service processes all
payments on *its* secure page, so your linked bank/PayPal is **never shown on
your site**. Create a free account, add your payout method there (private to your
dashboard), copy your page URL, and drop your username into the coffee link.
Ko-fi works identically if you prefer it.

## Images note

Use your own photos or licensed images. Manufacturer aircraft photos are usually
copyrighted and company logos are trademarks, so don't publish "every public
image" you find.

## Run it locally

Open `index.html` in a browser. For the PDF viewer to behave exactly like
production, serve it locally:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## File map

```
.
├── index.html          # all content + SEO
├── css/styles.css      # theme, layout, animations
├── js/main.js          # nav, scroll reveal, lightbox
├── assets/
│   ├── img/            # placeholder images + favicon
│   └── docs/           # resume.pdf (yours) + cover-letter.pdf (placeholder)
├── robots.txt
├── sitemap.xml
├── site.webmanifest
└── README.md
```
