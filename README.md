# aryankhamar.dev

Source of **[aryankhamar.dev](https://aryankhamar.dev)**, the portfolio of Aryan Khamar, a freelance full-stack developer based in Ahmedabad, India, working remotely with clients worldwide.

## What it is

A hand-written static site: plain HTML, CSS and JavaScript, no framework and no build step.

- **Pages:** home, a hire page and four case studies (CookOnCall, Kalokea, MY SOLAR Power, Shop'n Earn QA)
- **Performance:** self-hosted WOFF2 fonts, WebP images, lazy loading, about 220 KB for a full visit
- **Security:** strict Content Security Policy (hash-pinned inline script), HSTS, no third-party scripts
- **SEO and AI search:** canonical URLs, Open Graph and Twitter cards, JSON-LD (Person, ProfessionalService, FAQPage, BreadcrumbList), sitemap, `robots.txt` and `llms.txt`
- **Accessibility:** semantic landmarks, alt text, visible focus, light and dark themes

## Structure

```
index.html                         home page
freelance-full-stack-developer/    hire page
work/<project>/                    case studies
styles.css, script.js              shared styles and behaviour
fonts/, images/                    self-hosted assets
_headers, _redirects               Netlify security headers and redirects
robots.txt, sitemap.xml, llms.txt  search and AI crawler files
```

## Run locally

Any static server works, for example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000. The security headers in `_headers` only apply on Netlify.

## Deploy

Hosted on Netlify with the custom domain aryankhamar.dev.

## Contact

- Website: [aryankhamar.dev](https://aryankhamar.dev)
- LinkedIn: [linkedin.com/in/aryan-khamar](https://linkedin.com/in/aryan-khamar)
- Email: aryankhamar20@gmail.com

© 2026 Aryan Khamar. All rights reserved. The text, photos and resume are personal content and may not be reused.
