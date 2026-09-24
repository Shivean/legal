# Legal

Privacy policies for published Android apps, served over GitHub Pages.

Live at <https://shivean.github.io/legal/>

## Layout

One directory per app, each with its own `index.html`:

```
index.html          landing page, links to each app
pdftools/           PDF Toolkit — com.shiva.pdftools
arrowdrift/         Arrow Drift — com.arrowdrift.game
thinktwice/         Think Twice — com.trickygame.thinktwice
```

## Adding a new app

1. Create a directory named after the app.
2. Put an `index.html` in it.
3. Add a link to it in the root `index.html`.

The policy URL for Play is then `https://shivean.github.io/legal/<app>/`.

## Notes

This repository is public on purpose: Google Play requires a privacy policy URL that is
reachable without signing in. It holds no source code.

A policy has to keep matching what the app actually does — if an app starts collecting
something it did not before, such as adding analytics, the policy needs updating in the same
release.
