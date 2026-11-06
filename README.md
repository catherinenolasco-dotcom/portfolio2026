# Catherine Nolasco | People Operations portfolio

A static, single-page portfolio for Director and Head of People Operations roles.

- `index.html` is the finished page (fonts and photo embedded). Open it in a browser or host it with GitHub Pages.
- `src/` holds the build scripts: `content.py` (all text), `art_svgs.py` (illustrations), `extras.py` (interactive samples), `build_portfolio.py` (page template).
- To rebuild: `npm i @fontsource/dm-sans @fontsource/figtree`, then `FONTSOURCE_DIR=node_modules/@fontsource python3 src/build_portfolio.py index.html standalone`.

Contact: catherine.nolasco@gmail.com | linkedin.com/in/catherinenolasco

## Optional files

- `Catherine_Nolasco_Resume.pdf`: drop your resume PDF in the repo root. A "Download resume" button appears on the live site automatically once the file exists. Nothing shows if it is missing.
- `og.png`: the 1200 by 630 preview image used when the link is shared on LinkedIn, Slack, or email. Replace it any time with the same name.

## Per-company links

Add `?for=CompanyName` to show a "Why I would be a strong fit" box and a banner. Add `&note=Your one sentence` for a personal line, and `&view=quick` for the short version.
