# Coleman Metal Buildings LLC — Design System

**Family-owned. Engineered to last. Built right the first time.**

Coleman Metal Buildings LLC is a custom metal building contractor headquartered in **Kingston, Oklahoma**. They design and erect pole barns, porches, decks, shop buildings, warehouses, hay barns, RV covers, equipment sheds, and just about any structure that can be framed in steel.

This is their brand and design system — a single source of truth for how Coleman shows up across the website, yard signs, truck wraps, quote packets, business cards, and social.

---

## Brand at a glance

- **Headquarters:** Kingston, OK
- **What they build:** Custom metal buildings — pole barns, porches & decks, shop buildings, warehouses, equipment sheds, hay barns, RV covers, lean-tos, garages
- **Service area:** Southern Oklahoma & North Texas (Lake Texoma region)
- **Audience:** A mix of rural landowners, homeowners adding outdoor structures, and small business owners needing shop space
- **Personality:** Family-owned, trustworthy, handshake-deal. Heritage Americana. Polished-pro voice.

---

## Voice & content fundamentals

**The voice is polished-pro with a handshake underneath.** Coleman is not folksy or down-home — they speak like a confident craftsman who takes the work seriously. But they're also family-owned, so the writing never reads corporate, slick, or "marketing." If a sentence sounds like a sales pitch, rewrite it as a statement of fact.

**Tone rules**
- Confident, declarative sentences. No hedging.
- "We" not "I." Refer to the customer as "you," directly.
- No exclamation points except in calls to action ("Get a quote!" is fine; "Built tough!" is not).
- No emoji. Ever. Not in the website, not in social, not in email.
- Sentence case for body copy. **ALL CAPS reserved for short labels, signage, and headline rails.**
- Title case for navigation labels and product/service names.

**Casing examples**
- ✅ "Custom metal buildings, engineered to last."
- ✅ "POLE BARNS · PORCHES · SHOPS" (a label rail)
- ✅ "Built in Kingston, OK since 2014"
- ❌ "Built Tough. Built Right. Built Here." (too sloganey, too punchy)
- ❌ "Y'all need a barn?" (wrong voice — that's not Coleman)

**Sample copy**

> **Headline:** Custom metal buildings, engineered to last.
> **Sub:** Pole barns, porches, shops, and just about anything else you can frame in steel. Family-owned in Kingston, OK.
>
> **Service card:** Pole Barns — From 30×40 utility barns to fully enclosed equipment storage, we engineer every barn to the wind and snow loads your property actually sees.
>
> **Trust line:** Every Coleman building ships with a 40-year panel warranty and a written workmanship guarantee.
>
> **CTA:** Request a quote → / Talk to a builder →

**Words we use:** build, frame, engineered, custom, structure, span, pitch, panel, gauge, anchor, footing, workmanship, warranty, handshake, family-owned, since 2014, Kingston.

**Words we avoid:** tough, badass, killer, awesome, amazing, world-class, premium (overused — only on quote packets), solutions, partners, journey, experience, unlock, empower.

---

## Visual foundations

### Palette
The system runs on a **dark-grounded Americana** palette: deep ink as the ground, **barn red** as the single hot accent, **cream** as the canvas, and **cool steel** as the workhorse neutral.

| Token | Hex | Use |
|---|---|---|
| `--ink` | `#15171a` | Primary dark surface, body text on cream |
| `--barn-red` | `#b8351e` | Single accent — CTAs, the bar in the wordmark, ALL-CAPS labels, the red stripe in signage |
| `--cream` | `#efe8d7` | Default page background, paper |
| `--steel` | `#6b7280` | Body text on dark, secondary copy, dividers |
| `--steel-light` | `#a8b0b8` | Tertiary text, hairlines |
| `--bone` | `#f7f2e6` | Card surface on cream pages |
| `--rust` | `#8a2818` | Pressed/hover state of barn-red |
| `--patina` | `#3a4a52` | Cool-deep accent used sparingly behind imagery |
| `--gold` | `#c89545` | Reserved — warranty seals, quote-packet trim only |

**Rules**
- Barn red is the **only** hot color. Never two accent colors on one surface.
- Cream and ink can each play "ground" — pick one per surface and commit.
- Gold appears only on seals/badges (40-yr warranty, "Since 2014"), never as a fill or text accent at large size.
- Gradients are forbidden. Flat fills only. Heritage brands don't gradient.

### Type

Slab-serif Americana, no compromise.

- **Display:** **Alfa Slab One** — heavy block slab, ALL-CAPS or title case, for hero headlines, yard signs, the wordmark.
- **Subhead / industrial rail:** **Oswald** (semibold/bold) — condensed, ALL-CAPS, tight tracking. Used for section labels, eyebrows, navigation, the "POLE BARNS · PORCHES · SHOPS" label bands.
- **Body / serif:** **Zilla Slab** — readable slab serif for paragraphs, quote-packet body, longform.
- **Numeric / tabular:** **Zilla Slab** with `font-variant-numeric: tabular-nums lining-nums` for quote totals.

Tracking: tight on display (-0.01em), wide on small all-caps labels (+0.08em). No italics in display type. Light weights are forbidden — minimum 400 for body, 600+ for headings.

### Spacing & rhythm
8px base grid. Spacing tokens: 4 · 8 · 12 · 16 · 24 · 32 · 48 · 64 · 96 · 128. Pages breathe — generous vertical rhythm between sections (96–128px on web). Card padding is 32px minimum.

### Corners & edges
Coleman is a metal-and-wood brand. **Corners are mostly square.** 
- `--radius-0`: 0 (default for cards, photos, buttons on signage)
- `--radius-sm`: 2px (web buttons, form inputs — barely there)
- `--radius-md`: 4px (web cards, modal containers)

No pill shapes. No giant rounded blobs. The only round element in the system is the gold warranty seal.

### Borders, dividers, hairlines
- **Hairline:** 1px solid `--steel-light` — dividers between rows.
- **Heavy rule:** 4px solid `--ink` — the "I-beam rule" used to top section labels and the signature stripe on yard signs.
- **Red rule:** 6px solid `--barn-red` — the brand stripe. Always horizontal. Always at full bleed.

### Shadows
Almost none. This is a flat, printable system. The one exception:
- `--shadow-card`: `0 1px 0 rgba(0,0,0,.06), 0 8px 24px -12px rgba(21,23,26,.18)` — used only on web cards floating over imagery.

### Imagery
- **Photography style:** Warm, golden-hour, slightly desaturated. Wide horizons. Cattle-country light. Show the building IN ITS LANDSCAPE — never a clipped product shot.
- **What's IN the photos:** Finished pole barns at golden hour, builders on the job in Carhartts, trucks with the Coleman logo, real customer properties in southern Oklahoma. No stock people pointing at laptops.
- **No drawn illustrations.** Coleman is a real-world brand — every visual is either a photograph, a typographic composition, the wordmark, or a structural diagram (line drawings for spec sheets).
- **Treatment:** Photos full-bleed when hero; tight 4:5 or 16:9 crops in service cards. Never with rounded corners > 4px. Optional 1px ink border for thumbnails.

### Motion
Coleman is not an "animated brand." Web hover states are the only motion.
- Hover on red CTA: darken to `--rust`, 120ms ease-out.
- Hover on photo card: 1.02× scale on inner image, 200ms ease-out, mask never moves.
- Page entrances: 200ms fade-up on hero text, nothing else.
- No parallax. No marquee scrollers. No "as seen in" trust strips on auto-scroll.

### Layout principles
- **Wide containers, tall margins.** Web pages max out at 1280px content with ~80px gutters.
- **Always anchor the brand stripe.** The 6px red rule appears at the top OR bottom of nearly every surface — site header, yard sign, business card, page header on PDFs.
- **Section labels are eyebrowed.** Oswald ALL-CAPS, barn red, with a small 16×4 red bar to its left.
- **Photos do the heavy lifting.** Don't fill space with decorative SVG when a real job site photo would do the job better.

---

## Iconography

Coleman uses a **small, deliberate icon set** — never decorative, always functional. Stroke-based line icons at 2px stroke weight, square caps, no rounded corners. The set is sourced from **Lucide** (`https://unpkg.com/lucide@latest`) because its industrial line weight matches the slab type. Substitution is acceptable from Heroicons (outline) at 1.5px if Lucide is unavailable.

**When to use icons**
- Service categories on the website (one per service: barn, porch, shop, etc.)
- Spec lines in quote PDFs (dimensions, gauge, warranty)
- Contact strip: phone, email, location

**When NOT to use icons**
- In running paragraphs
- As decorative ornaments next to headlines
- Bullet lists (use a 4×4 barn-red square bullet instead)
- Emoji substitutes anywhere

Logos and seals are SVG. The wordmark is in `assets/logo-coleman.svg` with light and dark variants.

---

## File index

```
README.md                    ← this file
SKILL.md                     ← agent skill manifest
colors_and_type.css          ← all tokens + @font-face imports
assets/
  logo-coleman.svg           ← primary wordmark (dark on cream)
  logo-coleman-light.svg     ← light wordmark (cream on ink)
  mark-cm.svg                ← compact CM monogram mark
  seal-warranty.svg          ← gold 40-year warranty seal
  seal-since.svg             ← "Since 2014" round seal
  /photos/                   ← placeholder image slots used in mocks
fonts/                       ← @font-face fonts (loaded from Google Fonts CDN)
preview/                     ← Design System tab cards
ui_kits/
  website/                   ← marketing site (homepage + services)
mockups/
  yard-sign.html             ← job site / yard sign
  business-card.html         ← front + back
  social-square.html         ← Facebook/Instagram square posts
  quote-packet.html          ← quote / estimate PDF template
```

---

## Caveats

- **No source materials provided.** This system is built from scratch off your direction (heritage Americana, slab Americana type, family-owned voice). If you have an existing logo, photos, or color choices, send them over and I'll fold them in.
- **Fonts are Google-hosted substitutions** for self-hosted heritage faces. Alfa Slab One + Oswald + Zilla Slab is a strong pairing that ships free; if you want to license a paid pairing (e.g., Knockout + Tungsten + Caslon) say the word.
- **Placeholder seals** ("40-Year Panel Warranty," "Since 2014") use guessed dates and terms. Confirm before printing anything.
- **Phone number, address, and pricing are all placeholders.** Replace before going live.

## What I need from you to make this real

1. Confirm or correct **founded year, phone, exact address, service-area radius**.
2. Send **3–5 real photos** of finished jobs — even iPhone shots are fine. Real photography will lift this 10×.
3. Confirm the **40-year warranty** claim (or the actual terms).
4. Approve **Alfa Slab One** as the wordmark face, or send a logo if you already have one.
