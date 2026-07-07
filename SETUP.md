# Setup — 60 seconds

This folder **is** your GitHub profile repo. A repo named exactly after your
username (`pranavpanchal1326`) renders its README on your profile page.

## Steps

1. **Create the repo** on GitHub named `pranavpanchal1326` (must match your
   username exactly). Make it **public** and tick *"Add a README"* — or just
   push this folder.

2. **Fill the two TODOs** in `README.md`:
   - `your-email@gmail.com` → your real email
   - `RESUME_URL` → link to your résumé (a raw GitHub PDF link or your site)

3. **Push:**
   ```bash
   git init
   git add .
   git commit -m "profile: electric-blue terminal README"
   git branch -M main
   git remote add origin https://github.com/pranavpanchal1326/pranavpanchal1326.git
   git push -u origin main
   ```

4. Open `github.com/pranavpanchal1326` — done.

## Notes
- Images are in `/assets` and already wired with relative paths.
- If an image ever fails to load, use the absolute form:
  `https://raw.githubusercontent.com/pranavpanchal1326/pranavpanchal1326/main/assets/knight.jpg`
- The animated wordmark/tagline are live SVGs from readme-typing-svg — they
  need no setup and render for everyone.
- GitHub strips custom CSS, so glows/gradients aren't possible in a README.
  This matches the target's *layout, type, color, and terminal voice*. For the
  literal animated version you'd deploy a real page (Next.js on Vercel).
