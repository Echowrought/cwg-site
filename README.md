# cwg.echowrought.com

The CWG RPG hub: downloads, player tools, info and the leaderboard. Part of Echowrought Games.

```
public/index.html   the hub page
public/css/site.css shared Echowrought brand styles (copied from echowrought.com; keep in sync, don't fork the look)
public/css/cwg.css  hub-only styles
wrangler.jsonc      Cloudflare settings
```

Pushes to `main` deploy to cwg.echowrought.com automatically. Other branches get a preview link on their pull request.

## House rules

- Use the shared brand: colours, fonts and the header/footer from `site.css`.
- Never commit passwords, API keys or tokens (this repo is public). Secrets go in the Cloudflare dashboard.
- Download buttons point at each tool's `/releases/latest` in `cwg-rpg-community`, so publishing a new release updates the site with no code change.
