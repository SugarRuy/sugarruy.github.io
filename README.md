# Yanru Xiao

Academic homepage: https://sugarruy.github.io/

The homepage and full publication list are static pages built from `content.json`.
To update the site, edit that file and run:

```bash
python3 build.py
```

Commit the generated `index.html` and `publications/index.html` together with the
source changes. GitHub Pages serves the root of the `main` branch.

To preview locally:

```bash
python3 -m http.server 4173
```

## Theme

The site uses the MIT-licensed [AcademicPages](https://github.com/academicpages/academicpages.github.io)
theme stylesheet with a small static Python generator and local layout adjustments.
The compiled stylesheet is bundled, so Python is the only build requirement.
Theme source and revision are recorded in `theme-source.json`; see `LICENSE`.
