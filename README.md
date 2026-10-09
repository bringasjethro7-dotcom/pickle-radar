# Pickle Radar

Trial build of the Pickle Radar court finder (Metro Manila and Calabarzon).

- `index.html` is the whole site. `courts.json` is the court list it loads.
- This build is read-only: courts are added and edited in the Claude version, then `courts.json` is exported again.
- The site is marked "noindex" and `robots.txt` blocks search engines while listings are unverified. Remove both at launch.

## Put it online with GitHub Pages
1. Upload every file in this folder to the top level of the repository (branch `main`).
2. In the repository: Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", branch `main`, folder `/ (root)`, then Save.
3. After a minute or two the site is at `https://<your-username>.github.io/<repository-name>/`.
