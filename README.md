# WebLuxe High Fashion Boutique: Signature Royal demo

One of the two top-tier WebLuxe clothing-shop demos: a complete boutique on one page, in maroon and gold.
Live: https://webluxe.github.io/HighTier2_ClothingBoutique/

All pieces, prices, photos, names and addresses are examples. In demo mode the WhatsApp and call buttons show a popup instead of contacting anyone.

## What it has
- Opening curtain with a mandala and gold dust (short version on repeat visits)
- Silk-pleat curtain when you move between sections, rising gold dust in the hero
- Collection with categories, search, sort and quick view; wishlist and bag sent as one WhatsApp order
- Bride & Groom section, boutiques, booking form
- `/admin`: owner panel (demo mode keeps changes in the visitor's browser)

## Files
| File | What it does |
|---|---|
| `index.html` | The whole site |
| `data.js` | Products and announcements (written by the owner panel) |
| `tw.css` | Built styles. After adding new classes: `npx tailwindcss@3.4.17 -c tailwind.config.js -i tw.src.css -o tw.css --minify` |
| `demo/` | Demo mode, demo label and "Compare packages" |
| `admin/` | Owner panel |

Website built by [WebLuxe](https://webluxe.github.io/WebLuxe/).
