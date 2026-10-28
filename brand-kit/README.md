# CodesLytic Brand Kit

Single source of truth for brand assets: website, LinkedIn, social posts, reels, proposals, invoices, brochures, decks.

```
brand-kit/
  docs/brand-guidelines.md   Voice, logo rules, colour, type, layout, applications (start here)
  colors/                    colors.json, tokens.css, tailwind-theme.css, palette.html
  typography/                typography.css + fonts/ (Sora, Inter, IBM Plex Mono)
  logos/
    primary/                 horizontal + stacked logo (transparent PNG)
    icon/                    symbol only
    favicon/                 .ico + PNG sizes
    social/                  avatars, LinkedIn banner, logo on dark/light, OG image
  templates/                 HTML: social post, reel/story, carousel slide,
                             invoice, proposal, brochure tri-fold, email signature
  social/specs.md            Size cheat-sheet + content playbook
```

## Quick reference
- Orange `#FEA849` · Blue `#6DADFF` (dark) / `#0278E7` (light)
- Dark base `#0C0805` · Light base `#FFFDFB`
- Headings Sora · Body Inter · Code/labels IBM Plex Mono
- Tagline: Engineer. Transform. Scale.

## Using in code
- CSS: import `colors/tokens.css` and `typography/typography.css`.
- Tailwind v4: copy `colors/tailwind-theme.css` into `globals.css`.
- Templates link tokens by relative path; keep the folder structure.

## Known gaps
- Logos are raster PNG only. Get SVG/vector masters for print and large format.
- Logo gradient colours in `colors.json` are sampled approximations.
- Fill registered address, GSTIN and bank details once in `templates/invoice.html`.
