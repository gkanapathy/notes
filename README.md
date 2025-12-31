# notes

My personal landing page, built with Hugo and deployed to [kanapathy.com](https://kanapathy.com).

## Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Theme**: [hugo-coder](https://github.com/luizdepra/hugo-coder)
- **Deployment**: Cloudflare Pages (primary) + GitHub Pages (backup)

## Local Development

```bash
# Clone with submodules
git clone --recursive git@github.com:gkanapathy/notes.git

# Or if already cloned, initialize submodules
git submodule update --init --recursive

# Run local server
hugo server -D

# Build
hugo --minify
```

## Deployment

- **Primary**: Automatically deploys to [kanapathy.com](https://kanapathy.com) via Cloudflare Pages on push to `main`
- **Backup**: Automatically deploys to [gkanapathy.github.io/notes](https://gkanapathy.github.io/notes/) via GitHub Actions

## License

MIT
