# link-little

A link-in-bio page with no build step, no dependencies, and no third-party service. One HTML file, one config file. Fork it, edit your links, deploy it anywhere static files can live.

## Why

Linktree-style services insert themselves between you and your audience — branding, tracking, paid tiers for basic features. `link-little` is the 2-file version: you own the page, the domain, and the data (there is none).

## Use it

1. Fork or download this repo
2. Edit `links.config.js` — name, bio, avatar, links, optional theme colors
3. Deploy the folder to any static host:
   - **GitHub Pages:** repo → Settings → Pages → serve from `main`
   - **Vercel/Netlify:** import the repo, no build command needed
   - **Anywhere:** it's just `index.html` + `links.config.js`

## Customize

- Theme: uncomment the `theme` block in `links.config.js` and set `bg`, `card`, `border`, `text`, `muted`, `accent`
- Avatar: set `profile.avatar` to an image URL, or leave empty to get initials
- Want more than two files allows? That's the trade-off — this is deliberately minimal.

## License

MIT — do whatever you want with it.
