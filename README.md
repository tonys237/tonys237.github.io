# tonys237.github.io

The Kot Collective website (GitHub Pages, plain HTML and CSS). Live at https://tonys237.github.io/

| path | what |
|---|---|
| `/` | studio page with the Last Words: Moto Crash card |
| `/privacy/` | the game's privacy policy (approved by Tony, 10 October 2026) |
| `/support/` | contact and FAQ |
| `/app-ads.txt` | authorised ad sellers, served as plain text from the site root |
| `/config/lastwords-v1.json` | the game's remote settings (launch kill switches; how to change it: the game repo's `Docs/RemoteConfig.md`) |

No frameworks, no tracking, no cookies, no analytics, no web fonts or other files loaded from anyone else's server.

**App Store badge:** set `LIVE_STORE_URL` in `index.html` to the game's App Store link, and first save Apple's official
"Download on the App Store" badge (Apple Marketing Resources) as `assets/app-store-badge.svg`. Until then the card reads
"Coming soon to the App Store".

**Custom domain later:** add a `CNAME` file with the domain and point DNS at GitHub Pages; only the URLs change (the game's
`PRIVACY_URL` needs a new build, nothing else does).
