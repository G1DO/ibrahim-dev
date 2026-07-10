# Ibrahim Mohamed — Portfolio

Personal portfolio: projects, experience, blog, and contact.
Static HTML/CSS/JS — no build step, hosted on GitHub Pages.

## Structure

- `index.html` — home
- `projects.html` — all projects (flagship + grid)
- `project-raft-kv.html` — Raft KV case study (template for more case studies)
- `blog.html` — blog index with search + category filter
- `post-*.html` — blog posts (copy one as a template for new posts)
- `experience.html`, `contact.html`
- `assets/style.css` — all design tokens and shared styles

## Publishing changes

```
git add .
git commit -m "Update site"
git push origin main
```

## Notes

- Keep `favicon-*.png`, `apple-touch-icon.png`, `favicon.ico` from the old repo (pages reference them).
- Add your resume as `Ibrahim.pdf` in the repo root (all Resume buttons point to it).
- If your custom domain uses a `CNAME` file, keep that file in the repo root.
- To write a new blog post: copy any `post-*.html`, edit the content, then add a card for it in `blog.html` (and optionally on `index.html`).