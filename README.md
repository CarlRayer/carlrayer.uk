# carlrayer.uk

Sends visitors to **https://carlrayer.co.uk**, Carl Rayer Consulting's site
(repo `CarlRayer/carlrayer.co.uk`).

GitHub Pages serves this repo's `main` branch at `carlrayer.uk` (see `CNAME`), so the domain gets
HTTPS, which Netcetera's own forwarding can't give it. `index.html` redirects with a meta refresh
and names carlrayer.co.uk as the canonical page; `404.html` is the same page, so every path on
carlrayer.uk ends up there too. `www.carlrayer.uk` is a CNAME to `carlrayer.github.io.`, and Pages
redirects it to `carlrayer.uk`.

Nothing else belongs here. Change the site itself in `CarlRayer/carlrayer.co.uk`.
