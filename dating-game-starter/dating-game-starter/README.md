
# Dating Game – Starter

This is a no-command-line starter you can upload via GitHub's website to host your HTML dating game **for free** on GitHub Pages.

## 1) Create the GitHub repo (web only)
1. Go to https://github.com and sign in (create an account if needed).
2. Click **New** repository. Name it something like `dating-game`.
3. Keep it **Public** (required for Pages). Click **Create repository**.

## 2) Upload these starter files
1. Click **Add file → Upload files**.
2. Drag the entire folder contents from this ZIP into GitHub (you should see `index.html`, `data/`, and `images/` folders).
3. Click **Commit changes**.

## 3) Turn on GitHub Pages
1. Go to your repo **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Under **Branch**, choose `main` (or `master`) and set the folder to `/ (root)`.
4. Click **Save**.
5. Wait ~1 minute, then visit: `https://<your-username>.github.io/<your-repo>/`

## 4) Add your images
- Put your JPG/PNG files into `images/profiles/` using the **exact filenames** shown in the gallery (e.g., `001-HighVibeHealer.jpg`).  
- You can upload via **Add file → Upload files** and drag in batches.
- If you change a filename later, just update `data/profiles.json` to match.

## Notes
- The page automatically shows a placeholder if an image is missing.
- You can edit text right on GitHub (click the file → pencil icon → Commit changes).

## Optional: Faster CDN links
If you want, you can reference your images via jsDelivr CDN later without changing structure:
`https://cdn.jsdelivr.net/gh/<user>/<repo>/images/profiles/001-HighVibeHealer.jpg`
