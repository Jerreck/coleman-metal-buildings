---
name: coleman-metal-buildings-design
description: Use this skill to generate well-branded interfaces and assets for Coleman Metal Buildings LLC — a family-owned custom metal building contractor in Kingston, OK. Heritage Americana visual system. Use for marketing site work, quote packets, yard signs, business cards, social posts, email templates, and any other Coleman-branded artifact.
user-invocable: true
---

Read the README.md file within this skill, and explore the other available files.

If creating visual artifacts (slides, mocks, throwaway prototypes, etc), copy the assets out of `assets/` and load `colors_and_type.css` to inherit tokens, fonts, button/card classes, and the eyebrow/rail/stripe primitives.

Key files to reference:
- `README.md` — full brand foundation, voice, content rules, visual rules, iconography
- `colors_and_type.css` — every design token + Google-font imports (Alfa Slab One / Oswald / Zilla Slab)
- `assets/logo-coleman.svg` · `assets/logo-coleman-light.svg` — primary wordmark (dark + light)
- `assets/mark-cm.svg` — square CM monogram for avatars / favicon
- `assets/seal-warranty.svg` · `assets/seal-since.svg` — gold and cream commemorative seals
- `ui_kits/website/index.html` — full marketing-site reference
- `mockups/` — yard sign, business card, social posts, quote packet — each a working template

Visual rules at a glance:
- Palette: `--ink #15171A`, `--barn-red #B8351E`, `--cream #EFE8D7`, `--steel #6B7280`. Barn red is the ONLY hot accent. Gold is reserved for seals.
- Type: Alfa Slab One (display) · Oswald (rail/labels, uppercase) · Zilla Slab (body). No italics in display. No light weights.
- Corners: square by default. 2–4px radius for web only. Only round element is the warranty seal.
- Brand stripe: 6px solid `--barn-red` at the top or bottom of nearly every surface.
- No gradients. No emoji. No drawn illustrations — Coleman is a real-world brand.
- Photography: warm golden-hour, building in landscape, real Carhartts.

If the user invokes this skill without any other guidance, ask them what they want to build or design, ask some questions, and act as an expert designer who outputs HTML artifacts _or_ production code, depending on the need.
