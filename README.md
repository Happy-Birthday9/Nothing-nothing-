# Media Save — Final

Features added without changing the existing visible text/design:
- Custom logo from the supplied ImgBB image link, proxied through `/api/logo`
- PWA install button above `⚡ Fast • Simple • Beautiful`
- Install button hides after installation / standalone mode
- App name: Media Save
- PWA manifest + service worker
- TikTok downloader remains supported
- Public Facebook / Facebook Reels links are accepted without adding a new visible feature label
- Optional `FASTSAVER_API_KEY` environment variable can be added for more reliable Facebook public-video resolution
- Existing animations, colors, emojis and page text are preserved

Run:
1. `npm install`
2. `npm start`

For PWA installation, deploy over HTTPS (or localhost during development).

Optional Facebook API:
`FASTSAVER_API_KEY=your_key_here`
