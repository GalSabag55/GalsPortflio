# Gal Sabag — Portfolio

## Upload to GitHub Pages

Upload the **entire contents of this folder**, keeping the structure:

```
index.html
Gal_Sabag_Resume.pdf
images/            <- all 29 images
```

1. github.com → **+** → **New repository** → Public → Create
2. **Add file** → **Upload files** → drag `index.html`, `Gal_Sabag_Resume.pdf`
   and the whole `images` folder together → **Commit changes**
3. **Settings** → **Pages** → Branch: `main` → **Save**

## Editing content

All content lives in the `PROJECTS` array inside `index.html`.
Each project: `{ name, dir, desc, tags, ratio, img, hero, gallery, about, meta }`

- `dir` — `"rtl"` for Hebrew, `"ltr"` for English
- `ratio` — the image aspect ratio, e.g. `"2/3"`, `"3/4"`, `"4/3"`
- `hero:false` — hides the large image on the project page
- images live in `images/` — add a file, then reference it in `IMG`
