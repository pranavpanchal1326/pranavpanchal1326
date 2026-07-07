# Setup — 60 seconds

This folder **is** your GitHub profile repo. A repo named exactly after your
username (`pranavpanchal1326`) renders its README on your profile page.

## Steps

1. Create a **public** repo on GitHub named `pranavpanchal1326` (exact match).
2. Fill the two TODOs in `README.md`:
   - `your-email@gmail.com` → your real email
   - `RESUME_URL` → your résumé link (raw GitHub PDF, or your site)
3. Push:
   ```bash
   git init
   git add .
   git commit -m "profile: redesign"
   git branch -M main
   git remote add origin https://github.com/pranavpanchal1326/pranavpanchal1326.git
   git push -u origin main
   ```
4. Open `github.com/pranavpanchal1326`.

## Contents
```
README.md          the profile
LICENSE            MIT
assets/
  wordmark.png     designed name (Space Grotesk) — no animation, retina 2x
  aurora.jpg       hero banner
  knight.jpg       beside "About"
  void.jpg         closing strip
```

## Notes
- No animated SVGs, no third-party stat widgets — everything is your own asset,
  so nothing can break or rate-limit.
- If a relative image path ever fails, use the absolute form:
  `https://raw.githubusercontent.com/pranavpanchal1326/pranavpanchal1326/main/assets/wordmark.png`
- Section rules (`---`), the monospace `Selected work` index, and the `Craft`
  block are plain GitHub Markdown — they render identically for every visitor.
- GitHub strips custom CSS, so this is tuned to look premium *within* those
  limits: designed wordmark, tight index, real terminal blocks, cinematic art.
