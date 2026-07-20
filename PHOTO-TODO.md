# Photo TODO — Anchorline Website

## Founder Photo
- ✅ Code updated to use `images/murtaza.jpg`
- **Action needed:** Save the photo file to `anchorline/images/murtaza.jpg` then deploy

---

## Curtain Fabric Photos
These 3 products currently show intentional CSS placeholder tiles.
To add a real photo, set the `img` property in the products array in `index.html`.

| Product | Current placeholder class | Target img path |
|---|---|---|
| Tuscany Linen Weave | `p-linen` (tan gradient) | `images/tuscany-linen.jpg` |
| Midnight Velvet | `p-velvet` (dark velvet gradient) | `images/midnight-velvet.jpg` |
| Sheer Whisper Voile | `p-sheer` (ivory gradient) | `images/sheer-voile.jpg` |

**How to add:** In `index.html`, find the curtains product entries and change `img:''` to `img:'images/your-photo.jpg'`.

---

## Open Graph / Social Share Image
- Current OG image: `https://anchorline.in/images/carpet5.jpg` (Retro Links carpet)
- Consider creating a branded 1200×630px image for better social previews
- **Location:** `index.html` `<head>` — `og:image` and `twitter:image` meta tags

---

## Placeholders Still Needed (non-photo)
- `GST: [INSERT_GST_NUMBER]` — footer in `index.html`
- `CIN: [INSERT_CIN]` — footer in `index.html`
- `[INSERT_LINKEDIN_URL]` — footer Connect column in `index.html`
- ~~`[INSERT_INSTAGRAM_URL]`~~ — ✅ Set to `https://www.instagram.com/anchorline.in`
- Meta Pixel ID — `index.html` head (commented out, search `META_PIXEL_ID`)
- LinkedIn Partner ID — `index.html` head (commented out, search `LINKEDIN_PARTNER_ID`)
- GA4 Measurement ID — `index.html` head (commented out, search `GA_MEASUREMENT_ID`)
