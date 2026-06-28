# FatCat Asset Management

Parent company hub. Static site hosted on GitHub Pages.

## Deploy

1. Push to GitHub
2. Settings → Pages → Source: main branch, root
3. Site live at `https://[username].github.io/fatcatam`

## Custom domain

1. Add CNAME file with `fatcatam.com`
2. In Squarespace DNS: CNAME `www` → `[username].github.io`, A records → GitHub IPs
3. Enable HTTPS in repo settings

## Update links

Edit `index.html` href values when NOD domain is live.
