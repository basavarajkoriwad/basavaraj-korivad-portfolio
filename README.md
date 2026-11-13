# Basavaraj Korivad: AI Filmmaker Portfolio

One-page portfolio site with featured Instagram reels, toolkit, process, projects and contact details.

- `index.html`: the whole site (HTML, CSS and a small copy-button script, no build step)
- `Basavaraj_Korivad_Resume.pdf`: one-page resume
- `build_resume.py`: the script that generates the resume PDF (needs `reportlab`)

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Publish on GitHub Pages

1. Push this repo to GitHub.
2. Open **Settings, Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Update the reels

Each reel is an `<a class="reel">` block in `index.html`. Copy one, change the link, title and caption.
