# Fashion Tech Index

Thesis website by Sana Tahir (MS Media Innovation and Data Communication, Northeastern University).

Plain HTML and CSS, no build step.

## Pages
- `index.html` — homepage: dictionary definition of "fashion tech" and the latest blog post
- `blog.html` — the thesis feature
- `about.html` — why this project exists

## Deploy on Vercel
1. Create a new GitHub repository and upload every file in this folder. There are no subfolders, so you can select them all at once.
2. In Vercel, choose Add New > Project, import the repository, leave Framework Preset as "Other", and click Deploy.
3. `vercel.json` turns on clean URLs, so pages live at `/blog` and `/about`.

## Editing
- Article text: `blog.html`, inside `<div class="container">`. The conclusion goes where the dashed "Conclusion to come" box is.
- Photos in the article: copy the commented-out `mifigure` or `photogrid` examples near the end of the article.
- Colors and fonts: `style.css`, at the top.
- New images go in the top level of the repo, next to the HTML files.
