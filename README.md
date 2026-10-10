# Boris Belyavskiy — personal site

Source for my personal page: background, résumé and contact. Plain HTML and CSS, served by GitHub Pages with no build step.

## Structure

```
index.html                  one-page profile (hero, about, selected results)
assets/css/style.css        styles, light and dark
assets/img/                 headshot (jpg, webp), social preview, icons
assets/files/               résumé PDF
.nojekyll                   serve files as-is, skip Jekyll
```

## Updating

- **Résumé:** replace `assets/files/Boris-Belyavskiy-Resume.pdf` and keep the file name, so existing links keep working.
- **Text:** edit `index.html`, then update the "Updated" month in the footer.
- **Preview locally:** `python -m http.server 8765` in this folder, then open http://127.0.0.1:8765.

## Roadmap

Motivation · work case studies · research insights · projects · industry, company and product memos.
