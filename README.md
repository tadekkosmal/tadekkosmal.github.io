# Tadek Kosmal website refresh

This folder is a drop-in visual refresh for `tadekkosmal.github.io`, inspired by the compact academic presentation of Charles Wade's al-folio site while keeping the existing Jekyll content and asset paths.

## Install

1. Back up the repository or create a new Git branch.
2. Copy everything in this folder into the repository root, preserving the folders.
3. Ensure the existing navigation file is located at `_data/navigation.yml`.
4. Place the CV PDF at `assets/documents/Tadek_Kosmal_Resume.pdf`, or change `resume_pdf` in `_config.yml`.
5. Commit and push. GitHub Pages will rebuild the site automatically.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000`.

## Notes

- Existing `_posts`, `_random`, and `assets/images` content can remain unchanged.
- The local layouts intentionally override the old Minimal Mistakes layouts, so no remote theme is required.
- The color-mode toggle follows the system setting on first load and remembers the visitor's selection.
