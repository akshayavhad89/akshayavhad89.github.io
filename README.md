# Akshay Avhad, PhD · Engineering portfolio

A static GitHub Pages portfolio for industrial automation, digitalisation and autonomous manufacturing. The site uses HTML, CSS and vanilla JavaScript. The only external presentation dependency is the optional Google Fonts stylesheet. System fonts are available as a fallback.

## Publish on GitHub Pages

1. Create or open a public GitHub repository. Copy `docs/`, `README.md`, `CONTENT.md` and `.gitignore` into its root.
2. Commit and push those files to `main`. The site entry point should be at `docs/index.html`.
3. On GitHub, open **Settings → Pages** and select **Deploy from a branch**.
4. Select **main** and **/docs**, then save. GitHub shows the live URL in **Settings → Pages** once deployment succeeds.

GitHub's [publishing source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) covers user and project sites. All local links are relative, so this site works at either a user-site root or a project-site subpath.

## Edit or preview

- `docs/index.html` contains the site content, including roles, projects and publications.
- `docs/styles.css` controls layout, typography and the two colour palettes.
- `docs/theme.js` applies the saved or system theme before the first paint. `docs/main.js` handles the theme toggle, mobile menu, filters and motion.
- `docs/assets/akshay-avhad-cv.pdf` is the public CV offered by the download links.
- `CONTENT.md` records source decisions and optional placeholders.

Open `docs/index.html` in a browser for a quick preview. To preview over HTTP, run `python -m http.server 8000 --bind 127.0.0.1 --directory docs` from the repository root and open [the local preview](http://127.0.0.1:8000/). Stop the server with Ctrl+C.

The Pages source contains the public CV, a smart manufacturing profile illustration in the hero, the supplied professional portrait and a conceptual Swarm Production factory illustration. The work section includes two prototype video links and brief automation project summaries. The original CVs, reference letters and publication PDFs are kept outside `docs/` and are not published.
