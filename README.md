# Vanessa Flores — portfolio site

Single-page portfolio for Vanessa Flores, creative director and brand designer (Los Angeles).
Built with Claude Code as plain HTML/CSS/JS — no framework, no build step. Deploys to GitHub Pages as-is.

## Structure
- `index.html` — the whole site. Design tokens (colors, type) live in the `:root` block at the top of `<style>`; light and dark themes both defined.
- `images/` — project tiles (1200×900 JPG). To swap one, replace the file and keep the name; to add a row, copy an `<li class="row">` block in `index.html` and point its `<img>` at the new file.



## Deploy to GitHub Pages
1. Create an empty repo on GitHub named `vanessaflores` (or any name).
2. In this folder:
   ```
   git remote add origin https://github.com/YOUR-USER/vanessaflores.git
   git push -u origin main
   ```
3. On GitHub: Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `/ (root)` → Save.
4. The site is live at `https://YOUR-USER.github.io/vanessaflores/` within a minute or two. Add a custom domain later under the same Pages settings if you want it on hookbridge.com.

## Editing
Everything is in `index.html`. Change copy directly; change colors by editing the tokens in `:root`. Keep both the light block and the two dark blocks in sync.
