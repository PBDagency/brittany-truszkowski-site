# BrittanyTruszkowski.com

Personal brand site for Brittany Truszkowski. Astro (static) on Vercel.

## Run it

```bash
npm install
npm run dev      # local dev server
npm run build    # production build into dist/
```

Every push to GitHub deploys automatically: `main` goes to production, any other branch gets its own preview URL.

## Where things live

| What | File |
| --- | --- |
| Site name, SEO title/description, LinkedIn, email, nav | `src/site.ts` |
| Colors, fonts, buttons | `src/styles/global.css` |
| Homepage | `src/pages/index.astro` |
| Header / footer / desert ridgeline | `src/components/` |
| Person + WebSite schema, meta tags | `src/layouts/Base.astro` |
| Hero portrait | `src/assets/brittany-portrait.jpg` |

## Brand system ("Unforgettable" desert direction)

- Midnight Navy `#0E2A3A`, Copper Clay `#C46A4A`, Sandstone `#E8D3C1`, Ivory `#FAF7F2`, Sage `#5A7D6B`, Charcoal `#2B2B2B`
- Accessible working shades: copper-ink `#A8553A` (buttons, small copper text on ivory), copper-light `#D98A6C` (copper text on navy), sage-ink `#4A6A5A`
- Playfair Display (headlines), Montserrat (nav, buttons, labels), Source Sans 3 (body), Allura (the one handwritten accent)

## Before launch

- [ ] Replace the placeholder portrait with real photography (golden-hour desert shoot recommended)
- [ ] Confirm all homepage copy with Brittany
- [ ] Add LinkedIn and contact email in `src/site.ts`
- [ ] Build About, Speaking (with inquiry form), The Legal COO, Causes, Insights
- [ ] Expand Person schema (jobTitle, worksFor, sameAs) and add The Legal COO entity
- [ ] Set `indexable: true` in `src/site.ts` and connect the domain
