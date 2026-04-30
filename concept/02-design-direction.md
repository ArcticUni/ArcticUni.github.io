# ArcticUNI V2 — Design Direction

## DECISION: Option C — Ice White ✓

The aluminium can (`f9c7cf99-...-removebg.png`) on a white background is the hero.
The can's built-in gradient (bright silver top → deep navy bottom) *is* the color story.
No need to impose a palette — we extract it from the product itself.

---

## The core aesthetic choice (archived)

The current site mixes a dark navy header with **white/light content sections**.
That creates a split personality. We have two clear paths for V2:

---

### Option A — Full Dark (Nordic Editorial)
Match marinesparkx.github.io exactly. Deep navy throughout, teal accents, no white.

**Looks like:** High-end skincare / premium supplement brands (Voya, Wild Nutrition)
**Feeling:** Luxury, Arctic, serious science
**Risk:** Can feel heavy / clinical if not done well
**Images needed:** Dark product photography or light product on dark background

---

### Option B — Dark Hero, Light Body (Current pattern, refined)
Keep the dark hero section with the Arctic ocean photo, switch to a clean warm-white
body with navy text. Teal accents carry through.

**Looks like:** Scandinavian lifestyle brands (Fjällräven, Aesop)
**Feeling:** Approachable premium, natural, clean
**Risk:** Harder to make cohesive with Marine Spark X branding
**Images needed:** Lifestyle shots, clean product photography on white/cream

---

### Option C — Ice White (Minimal)
Bright, almost clinical white. Very clean grid. Arctic = cold = white. Small teal
and gold accents only.

**Looks like:** Laboratory precision, pharma-adjacent premium
**Feeling:** Trustworthy, scientific, Korean-market friendly (K-beauty aesthetic)
**Risk:** Loses the "Arctic nature" warmth
**Images needed:** Clean product shots, abstract ice/water textures

---

**My recommendation:** Option A or B.
Option A if B2B / investor-facing. Option B if B2C / consumer-facing.

---

## Typography (inherit from marinesparkx)

These fonts are already loaded in the marinesparkx scaffolding — free to reuse:

- **Display / Headlines:** Cormorant Garamond — serif, elegant, weight 300 for large sizes
- **Body / UI:** DM Sans — geometric sans, clean and modern

The current ArcticUNI site uses Inter — fine but generic. Cormorant Garamond elevates it.

## Color palette options

### Inherit from Marine Spark X (easiest, most cohesive)
- Background: `ocean-950` (#040f17)
- Cards: `ocean-900` (#070e1a)
- Body text: `ocean-100`
- Accent: `teal-400` / `teal-300`

### ArcticUNI-specific variation (adds brand distinctiveness)
Keep the ocean palette but add an **ice/glacier blue** accent alongside the teal:
- Primary accent: `teal-400` (same as MSX)
- Secondary accent: `sky-200` or `blue-200` (glacier ice, lighter/cooler)
- Gold highlight: `amber-300` / `yellow-200` (for certifications, trust signals)

Gold is already used in the current site (`#c9a84c`) for quality indicators — keep it.

## Product photography — what we have vs. what we need

### Currently in the concept folder:
- `f9c7cf99...` — finished product can (good for hero)
- `b66caf8c...` — another product shot
- `263db1db...` — capsule / powder shot
- `4df6b6d2...` — scenic / context shot
- `e2bebd41...` — scenic shot

### Gaps (brainstorm — what would help):
- Arctic landscape / ocean horizon photo (wide, hero-worthy)
- Product on dark slate or ice surface (editorial)
- Close-up of capsule for ingredient section
- Process shot (lab, analysis, harvest)

**Question for you:** Do you have more photos, or would we work with what's here?
