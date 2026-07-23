# Azib — 30 & 90 Day SE Review

Interactive onboarding review page for Solution Engineer 30-day review and 90-day goals.

## Local

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8765
```

## Deploy on Render (Static Site)

1. Push this repo to GitHub.
2. In [Render Dashboard](https://dashboard.render.com) → **New** → **Static Site**.
3. Connect the GitHub repo.
4. Settings:
   - **Branch:** `main`
   - **Build Command:** leave empty (or `true`)
   - **Publish Directory:** `.`
5. Create Static Site → wait for deploy → open the `*.onrender.com` URL.

Or apply the included `render.yaml` Blueprint from the dashboard (**New** → **Blueprint**).
