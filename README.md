# Sean's Homepage

Personal website / blog of sjduan.  
Live: https://sjduan.github.io

---

## About
This is a lightweight personal website for sharing projects, blog posts, and notes. Built as a static site so it's fast, easy to maintain, and ideal for hosting on GitHub Pages.

## Features
- Simple, responsive design
- Blog posts (Markdown)
- Projects showcase
- Contact / social links
- RSS feed and SEO-friendly meta tags

## Tech stack
Choose one that fits your repo; examples:
- Static HTML/CSS/JS
- Jekyll (Ruby) — default for GitHub Pages
- Hugo (Go)
- VitePress / Astro / Eleventy

## Local development (examples)

### Jekyll
```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

### Hugo
```bash
brew install hugo
hugo server -D
# open http://localhost:1313
```

### Plain static (npm)
```bash
npm install
npm run dev    # if using a bundler/dev server
```

## Deploy
- GitHub Pages: push to `gh-pages` or use `main` with `/docs` (see repo Settings → Pages).
- Netlify / Vercel: connect repo and enable automatic deploys.

## Structure
- `index.md` / `index.html` — homepage
- `_posts/` or `content/posts/` — blog posts (Markdown)
- `assets/` — images, CSS, JS
- `_config.yml` / `config.toml` — site config (if using a generator)

## Add a post
Create a markdown file in the posts folder with front matter:
```md
---
title: "My New Post"
date: 2026-03-19
tags: [notes, project]
---
Write your post here...
```

## Customization tips
- Update metadata (site title, description, social links) in the site config.
- Add Google Analytics / Plausible or use privacy-friendly alternatives.
- Use a minimal CSS framework (e.g. Pico.css) or a custom theme for faster styling.

## Contributing
This is my personal site — pull requests welcome for typos, accessibility fixes, or small layout improvements. For larger changes, open an issue first.

## License
Content © USERNAME. Site assets and code are under the MIT License (see `LICENSE`).

## Contact
- Email: you@example.com
- Twitter: @yourhandle
- GitHub: https://github.com/USERNAME
```

Would you like a shorter one-page README, or a Jekyll-specific README prefilled for your repo?Would you like a shorter one-page README, or a Jekyll-specific README prefilled for your repo?
