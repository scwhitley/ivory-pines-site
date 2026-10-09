# Ivory Pines Cleaning — website redesign

Astro rebuild of ivorypinescleaning.com. Same content, cleaner presentation.

## Run it
```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # outputs static site to dist/
```

## Where things live
| Change this | Edit this file |
|---|---|
| Phone, email, hours, socials, service areas, offer text | `src/data/site.json` |
| Service names and descriptions | `src/data/services.json` |
| Cleaning checklist tasks | `src/data/checklist.json` |
| FAQ | `src/data/faq.json` |
| Colors and fonts | `src/styles/global.css` (top of file) |
| Header / footer | `src/components/Header.astro`, `Footer.astro` |
| Home page sections | `src/pages/index.astro` |

## Before launch (TODO)
- [ ] Add photos: hero, service cards, Denton, before/after pairs (`public/images/`)
- [ ] Download logo into `public/logo.svg` and update `logo` in `site.json`
- [ ] Name the actual offer in `site.json` → `offer.highlight`
- [ ] Confirm Google rating in the trust strip; embed reviews widget
- [ ] Hook the quote form to their CRM/booking tool (currently Netlify Forms)
- [ ] Migrate blog posts, privacy policy, terms
- [ ] Set up redirects for any old URLs that change

## Deploy
Connected to Netlify: every push to `main` redeploys; every pull request gets a preview link.
