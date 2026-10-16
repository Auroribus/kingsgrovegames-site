# kingsgrovegames.com

The Kingsgrove Games website: plain HTML and CSS, served by GitHub Pages
from the root of `main`. Push to `main` and it's live within a minute or two.

- `index.html`: home (TILT, coming to Android)
- `privacy.html`: the privacy policy the Play listing links to. Update it
  before any build that adds analytics, crash reporting or ads ships.
- `contact.html`: contact and the Impressum (German law, § 5 DDG).
  The pink `[...]` placeholders still need the real name, address and phone.
- `CNAME`: the custom domain for GitHub Pages.

## DNS (Squarespace, Custom records)

The domain is registered at Squarespace and managed by Google Workspace.
Leave the Google Workspace records (MX, TXT, DKIM) alone. The site needs:

| Host | Type | Data |
|---|---|---|
| @ | A | 185.199.108.153 |
| @ | A | 185.199.109.153 |
| @ | A | 185.199.110.153 |
| @ | A | 185.199.111.153 |
| www | CNAME | auroribus.github.io |

No cookies, analytics or third-party fonts or scripts on the site: the
privacy policy says so, so keep it true.
