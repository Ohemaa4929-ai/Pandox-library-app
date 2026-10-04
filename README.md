# Pandox Market app

Static site hosted on Vercel from this GitHub repo. Every commit to `main` redeploys it.

## Files

| File | What it is |
|---|---|
| `index.html` | The app: Market, Catalog and Cart tabs |
| `new-arrivals.html` | Standalone page with barber chairs, salon mirrors, dinner sets and lighting. Photos are embedded in the file. Has a 180° view, an exploded view for chairs and WhatsApp ordering |
| `README.md` | This file |

## Price ranges (GH₵)

| Category | Range |
|---|---|
| Barber, styling, shampoo and dark premium chairs | 3,000 - 12,000 |
| LED salon mirrors | 2,000 - 2,900 |
| Dinner sets | 5,000 - 13,000 |
| Ceiling lights | 860 - 2,000 |
| Wall lights | 350 - 600 |

To change a price, open `new-arrivals.html` on GitHub, tap the pencil icon and edit the two numbers for that product in the `D` list near the bottom. Each row reads: id, name, category, image, minimum, maximum, dark premium flag.

## Deploy

1. Open the repo on GitHub.
2. Tap Add file, then Upload files. Choose the file and tap Commit changes.
3. Wait about a minute. Vercel builds and publishes.

## Rules that stop a build from failing

- Keep file names short, under 50 characters. Use letters, numbers, dashes and no spaces.
- Never upload a zip or unpack one into the repo. Upload the single files inside it.
- Put `index.html` and `new-arrivals.html` in the top folder, not inside another folder.
- Do not upload files named after a sentence or a pasted link. Vercel rejects names that are too long.
