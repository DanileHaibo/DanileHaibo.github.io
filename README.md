# Haibo Hu · Academic Homepage

Personal academic website for **Haibo Hu**

## Local preview

```bash
cd haibo-homepage
bundle install
bundle exec jekyll serve
```

Then open the URL shown in the terminal (usually `http://127.0.0.1:4000`).

## Deploy to GitHub Pages

1. Create a public repository named `DanileHaibo.github.io` (or any repo + GitHub Pages from `/` or `/docs`).
2. Push this folder to the default branch.
3. In **Settings → Pages**, set source to GitHub Actions / Deploy from branch.
4. Optional: set a custom domain in `CNAME`.

## Customize

| File | What to edit |
|---|---|
| `_data/profile.yml` | Name, bio, education, experience, awards, links |
| `_publications/**/*.md` | Papers |
| `assets/images/photos/profile.jpg` | Portrait photo |
| `assets/files/cv.pdf` | CV PDF |

Replace the placeholder portrait (`profile.jpg`) with your real photo for the best look.
