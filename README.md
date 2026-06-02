# ml-explained.github.io

WaveGuide is a Jekyll + Chirpy site hosted on GitHub Pages. It is designed to grow into a long-term portfolio, daily technical blog, and eventually a lightweight community around ML, photonics, chips, and practical AI systems.

## Repository map

- `index.html` — custom landing page with hero, latest writing, topic areas, and community roadmap CTA.
- `_pages/about.md` — personal profile, focus areas, highlights, and contact links.
- `_pages/portfolio.md` — project/case-study landing page.
- `_pages/community.md` — plan for comments, GitHub Discussions, and future forum options.
- `_pages/archives.md`, `_pages/categories.md`, `_pages/tags.md` — Chirpy blog index pages.
- `_posts/` — Markdown blog posts using the `YYYY-MM-DD-title.md` naming convention.
- `assets/css/waveguide.css` — custom visual layer for the WaveGuide landing, portfolio, and community pages.
- `.github/workflows/pages-deploy.yml` — GitHub Pages build and deploy workflow.

## Publishing workflow

1. Create a new Markdown file in `_posts/` named `YYYY-MM-DD-title.md`.
2. Add front matter with `title`, `date`, `categories`, and `tags`.
3. Commit and push to `main`.
4. GitHub Actions builds the Jekyll site and deploys it to GitHub Pages.

## Community plan

GitHub Pages is best for the public static website. For user-generated posts, accounts, moderation, and persistent discussion data, connect an external community layer.

Recommended rollout:

1. Publish consistently on the blog.
2. Enable GitHub Discussions and add a GitHub-backed comment tool such as Giscus.
3. If readers need independent posts and profiles, move the community layer to Discourse, Supabase, Firebase, or a custom backend.
