# CodesLytic Brand Guidelines

## 1. Brand
- **Name:** CodesLytic (one word, capital C and L in running text; logo wordmark is all caps).
- **Tagline:** Engineer. Transform. Scale.
- **What we are:** end-to-end technical delivery partner. We own the full lifecycle: problem discovery, solution design, build, deployment, staff training.
- **Audiences:** (a) enterprise/mid-large technical buyers (CTO, eng lead) needing DB migration, cloud data warehouse, ETL, PL/SQL work; (b) founders/SMB owners needing web/app/ERP builds.
- **Personality:** precise, calm, confident, practical. Engineer-to-engineer, never hype.

## 2. Voice
- Lead with the client's problem, not the tech stack.
- Concrete over vague: numbers, outcomes, named technologies.
- Short sentences. Active voice. No buzzword stacks ("synergy", "cutting-edge", "revolutionary").
- Show proof of full-lifecycle ownership (build, deploy, train).
- Never use client names or logos without confirmed permission.
- Hashtags: max 3-5, e.g. #DataEngineering #ERP #PostgreSQL #AWS #Automation.

## 3. Logo (`logos/`)
| File | Use |
|---|---|
| `primary/logo-horizontal.png` (2172x724, transparent) | Default. Headers, documents, invoices, decks, signatures |
| `primary/logo-stacked.png` (1254x1254, transparent) | Square spaces, covers, posters |
| `icon/icon-mark.png`, `icon-mark-square.png` | The "C + </>" symbol alone: avatars, favicons, tight spaces |
| `favicon/` | favicon.ico + 16/32/48/64/180/192/512 PNGs |
| `social/` | Ready avatars (dark/light, 1080), LinkedIn banner 1584x396, logo on dark/light, OG image |

Rules
- Works on both dark (`#0C0805`) and light (`#FFFDFB`) backgrounds. Prefer dark; it is the hero look.
- Clear space: at least the height of the "C" bar's thickness (about 1/8 of logo height) on all sides.
- Min size: horizontal 120 px wide (digital) / 30 mm (print); icon 16 px.
- Use the horizontal logo when the tagline must stay legible (width >= 300 px); otherwise use the icon.
- Do not: recolour, stretch, rotate, add extra shadows/outlines, place on busy photos or on mid-orange/mid-blue backgrounds, retype the wordmark in a font.
- Source files are raster PNG. For print/large-format, request a vector (SVG/AI) master from the designer; see TODO in README.

## 4. Colour (`colors/`)
Orange and blue come from the logo's two halves: orange = engineering/build, blue = data/cloud/scale. Orange leads; blue supports. Neutrals are warm.

| Role | Dark bg | Light bg |
|---|---|---|
| Primary accent | Orange `#FEA849` | Orange `#FEA849` (fills), `#975A05` (small text) |
| Secondary accent | Blue `#6DADFF` | Blue `#0278E7` (text `#0267C7`) |
| Background | `#0C0805` / `#1E1A15` | `#FFFDFB` / `#F9F2EB` |
| Surface | `#15110C` / `#211C17` | `#FCF6EE` / `#EDE7DF` |
| Border | `#423C35` | `#D9D3CC` |
| Text | `#FCFAF7` / `#B7AEA4` / `#92897F` | `#110C08` / `#524A41` / `#70675E` |
| Success | `#34D399` | `#047857` |

Guidelines
- Proportion: ~70% neutral, ~20% orange, ~10% blue.
- Text on an orange fill is `#15110D` (9.76:1). Never white on orange.
- Orange as text on light backgrounds must be `#975A05` (passes 4.5:1); `#FEA849` fails there.
- Brand gradient: orange to blue at 135deg. Use for one highlight word, divider or shape per layout, not as full backgrounds of text blocks.
- Files: `colors.json`, `tokens.css` (CSS variables, dark/light), `tailwind-theme.css` (Tailwind v4), `palette.html` (visual swatches).

## 5. Typography (`typography/`)
| Role | Font | Weights |
|---|---|---|
| Display / headings | **Sora** | 700, 800 (600 for subheads) |
| Body / UI | **Inter** | 400, 500, 600 |
| Code / labels / eyebrows / numbers | **IBM Plex Mono** | 400, 500 |

All three are free (SIL OFL), included in `typography/fonts/`. Install them on your machine for Canva/Figma/Word/PowerPoint.

Scale (web): H1 48-72, H2 32-40, H3 24, body 16-18, small 13-14, eyebrow 12 uppercase, tracking 0.14em. Headings tight (-0.02em, line-height 1.1); body line-height 1.6.
Fallback when fonts unavailable (email, Google Docs): Arial / Calibri for body, Arial Bold for headings.

## 6. Layout and graphic style
- Dark, editorial, spacious. Generous margins (8-10% of canvas).
- Radius: cards 12 px, panels 30 px, buttons/tags pill (9999 px), inputs 4 px.
- Shadows soft and dark: `0 4px 16px rgba(0,0,0,.35)`.
- Soft radial glows (orange bottom-left, blue top-right at 20-30% opacity) as background accent.
- Thin orange rule (4-6 px) as section marker; mono uppercase eyebrow above headlines.
- Icons: outline, 1.5-2 px stroke, rounded caps (Lucide style). No emoji in client documents.
- Imagery: real product screenshots, architecture/data-flow diagrams, team photos. Avoid generic stock handshakes.

## 7. Applications and formats
### Social (`templates/`, `social/specs.md`)
- Always: logo bottom corner, eyebrow label, one idea per post, URL `codeslytic.com`.
- Keep text inside safe zones (Reels/Stories: 250 px top, 340 px bottom free).
- Video/reels: first 2 s hook on screen as text, brand intro sting <= 1 s (icon on `#0C0805`), end card with logo + CTA, captions always on.
### Proposals
Cover (dark) → problem → solution & approach → phases/timeline → investment → terms → next steps. 4-8 pages. Template: `templates/proposal.html`.
### Invoices
Light background, orange header rule, black table header, blue total. Fill GSTIN/bank details once and save as master. Template: `templates/invoice.html`.
### Brochures
A4 landscape tri-fold: services / why us / cover, then proof / process / contact. Template: `templates/brochure-trifold.html`.
### Email signature
`templates/email-signature.html`.

## 8. Contact block (use consistently)
- Web: codeslytic.com
- Email: info@codeslytic.com
- WhatsApp: +91 95655 55541
