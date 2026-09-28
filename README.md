# Aditya Ramesh

Personal site built with [Hugo](https://gohugo.io/) and the [Today I Learned theme](https://github.com/michenriksen/hugo-theme-til).

Live at [rameshaditya-me.github.io](https://rameshaditya-me.github.io/).

## Local development

**Prerequisites:** [Hugo Extended](https://gohugo.io/installation/), [Go](https://go.dev/dl/) (for Hugo modules), and [Node.js](https://nodejs.org/) (theme JS build dependency).

```bash
# Install JS dependencies (required by the theme build)
npm install

# Download theme module
hugo mod get

# Start dev server
npm run dev
```

Open [http://localhost:1313](http://localhost:1313).

## Content

| Section | Path | Purpose |
|---------|------|---------|
| **News** | `content/news.md` | Homepage news / updates |
| **Notes** | `content/notes/` | Short tips and discoveries |
| **Posts** | `content/posts/` | Longer-form writing |

## Deploy

Pushes to `main` build with GitHub Actions and publish to GitHub Pages at [rameshaditya-me.github.io](https://rameshaditya-me.github.io/).

Before the first deploy, in the GitHub repo go to **Settings → Pages** and set **Source** to **GitHub Actions**.
