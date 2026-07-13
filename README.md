# LMC Remote — Landing Page

Single-file landing page for both LMC Remote and Media Remote, matching the
Lazzaro Standard design language across the portfolio.

## Deploy

```
johnlaz.github.io/mediaremote/
├── index.html
└── assets/
    ├── LMCremote.zip           ← LMC Remote (full room build)
    ├── mediaremote.zip         ← Media Remote (PC only)
    ├── screenshot-room.png     ← Room tab screenshot (hero image)
    └── screenshot-media.png    ← Media PC tab screenshot (hero image)
```

The two screenshots are referenced by the page but NOT included in this zip
since they come from your own device. Grab them from the uploads in this
session and drop them in assets/ alongside the zip files. They display
side-by-side in the hero on desktop, just the Room tab on mobile.

## Updating for a new build

1. Replace the relevant zip in `assets/`
2. Update version badge in the hero eyebrow (`v5.6 · Windows · fully local`)
3. If the feature list changed, update the `<ul class="feature-list">` inside
   the relevant product card

## Structure

| Section | What it is |
|---|---|
| Header | Sticky nav with anchor links |
| Hero | Headline, both download buttons, trust row, dual screenshot |
| What's Inside | Two product cards — LMC Remote (featured) and Media Remote |
| LMC Features | 6 feature cards covering what's new in the LMC build |
| Setup | 3 numbered steps — same for both builds |
| Downloads CTA | Both buttons with a one-line distinction |

## Screenshots

The page references `assets/screenshot-room.png` and
`assets/screenshot-media.png`. These are your own app screenshots — export
them from the uploads in this conversation and rename accordingly.

---
LMC Remote — © 2026 LAZLAB Creations
