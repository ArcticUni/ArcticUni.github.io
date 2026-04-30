# ArcticUNI V2 — Next Steps

## Decisions needed before we start building

Work through these in order — each one shapes the build:

### 1. Who is the primary audience?
- [ ] B2B distributors / partners (Korean market focus)
- [ ] B2C consumers (end-users buying supplements)
- [ ] Both equally

This affects: copy tone, CTA language, which sections to emphasize.

### 2. Design direction?
(See 02-design-direction.md)
- [ ] Option A — Full dark, Nordic editorial
- [ ] Option B — Dark hero, light body
- [ ] Option C — Ice white, clinical minimal

### 3. Hero layout?
(See 03-site-sections.md, Section 1)
- [ ] A — Full-bleed ocean photo + large headline
- [ ] B — Split layout, product visible immediately
- [ ] C — Centered minimal, coordinate-led

### 4. Contact section?
- [ ] Keep full form (more professional, captures info)
- [ ] Just email + LinkedIn (simpler, less friction)

### 5. Photography?
- [ ] Work with the images already in the concept folder
- [ ] Need to find/shoot more photos first (product on dark surface, Arctic landscape)

---

## What happens after decisions are made

1. **Scaffold the Astro project**
   Copy the marinesparkx.github.io structure into a new `ArcticUNI_V2` Astro project.
   This takes ~15 minutes — it's mostly copy-paste and rename.

2. **Set up GitHub repository**
   Create `arcticuni-v2` repo (or update the existing `ArcticUNI.github.io` repo).
   Push the scaffolded project. Enable GitHub Pages.

3. **Build sections one by one**
   Start with Nav + Hero (most visible). Then fill in the rest.
   You can preview the site locally with `npm run dev` at any point.

4. **Review and iterate**
   Share the preview link. Adjust copy, colors, spacing together.

5. **Go live**
   When happy: push to the GitHub Pages repo. Done.

---

## Technical: what "copying scaffolding" means exactly

From marinesparkx.github.io, we take:
- `package.json` — the list of tools (Astro, Tailwind, astro-icon)
- `astro.config.mjs` — Astro configuration
- `.github/workflows/` — the build pipeline (GitHub Actions deploy)
- `src/styles/global.css` — the Tailwind theme (ocean colors, fonts)
- `tsconfig.json` — TypeScript settings

We then create a fresh `src/pages/index.astro` for ArcticUNI's content
instead of copying Marine Spark X's content.

Images from the concept folder go into `src/assets/images/` so Astro
can auto-compress them.
