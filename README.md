# Tidio / Lyro Chat Page for GitHub Pages

This repository hosts a tiny HTML page that loads your Tidio (Lyro) chat widget,
so you can embed it in a Canva Website (which doesn't allow custom JavaScript).

## Files
- `index.html` — minimal page with your Tidio script.
- `README.md` — these instructions.

## How to publish on GitHub Pages
1. Create a new GitHub repo (e.g., `tidio-chatpage`).
2. Upload `index.html` and `README.md` to the root of the repo (branch `main`).
3. Go to **Settings → Pages**.
   - Under **Build and deployment**, choose **Deploy from a branch**.
   - Set **Branch**: `main`, **Folder**: `/ (root)`. Click **Save**.
4. Wait for the site to deploy. Your site will be available at:
   - `https://<your-username>.github.io/tidio-chatpage/`

If you instead name the repo `<your-username>.github.io`, your site will be available at `https://<your-username>.github.io/`.

## Embed in Canva
In your Canva website editor:
- Go to **Apps → Embed → Website**.
- Paste your GitHub Pages URL from above.
- Resize the embed block as needed. The chat bubble will appear within that embedded frame.

## Notes
- The script URL uses `https://` to avoid mixed-content issues.
- The chat widget will be confined to the embedded frame; it can't float over the entire Canva site.
- If you change the Tidio property or script key, update the `<script src="...">` in `index.html` and push again.
