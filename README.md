# World of Tat2face

One hub for every creative work by Chad James Kerns (TAT2FACE), Arizona: music, apps & games, books, brands, and a gallery of his art.

- Live: https://world-of-tat2face.vercel.app
- Static site in `site/` (plain HTML + CSS, no build step)
- Card thumbnails are real screenshots of each live site (1280×800, cropped); gallery uses Chad's real art assets.

## Local preview
```bash
cd site && python3 -m http.server 8080
```

## Deploy
```bash
cd site && vercel deploy --prod
```
