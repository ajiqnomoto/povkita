# Povkita (Wedding POV)

Static single-page photo/video gallery. Plain HTML + Tailwind CDN + Font Awesome, no build step.

## Run with Docker

```bash
docker compose up -d --build
# site at http://localhost:8081
```

## Run without Docker (dev preview)

```bash
python3 -m http.server 8081
# site at http://localhost:8081
```

## Files

- `index.html` — entire site (single file)

## Deploy

Pushes to `main` auto-deploy to GitHub Pages:
https://ajiqnomoto.github.io/povkita/
