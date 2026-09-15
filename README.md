# Bullet Tech — jvsena42.github.io

Company website for **Bullet Tech**, used as the developer/company domain on
Google Play Console. Static, no build step, served by GitHub Pages from the
`main` branch root.

- `index.html` — the whole site
- `assets/` — app icons and screenshots (pulled from the app repos, resized)
- `sitemap.xml`, `robots.txt`, `.nojekyll`

## Apps

| App | What it is | Repo |
| --- | --- | --- |
| Loopky | Flashcards with spaced repetition on Pubky identity (Android + iOS) | [jvsena42/loopky](https://github.com/jvsena42/loopky) |
| Mandacaru | Lightweight Bitcoin validator node for Android (Utreexo + Floresta) | [jvsena42/mandacaru](https://github.com/jvsena42/mandacaru) |

## Google Search Console verification

Play Console requires the site to be verified in Search Console first. Use a
**URL prefix** property for `https://jvsena42.github.io/` and either:

1. **HTML tag** — paste the `<meta name="google-site-verification" ...>` tag into
   the placeholder near the top of `index.html`, then push; or
2. **HTML file** — drop the `google<token>.html` file Search Console gives you in
   the repo root and push.

DNS verification is not available here, since the `github.io` domain is not ours.

## Local preview

```
python3 -m http.server 8000
```
