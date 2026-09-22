# tectonic.arpcentral.net

Static website for **Plates**, the road-trip licence plate game for Android.

- `index.html` – homepage, using the Play Store feature graphic
- `privacy.html` – privacy policy for the Play Store listing
- `images/` – feature graphic, icons, and screenshots copied from the Android app's `store/` and `art/` folders

Plain HTML and CSS with no build step. Deployed on Netlify from the `main` branch of
`github.com/jarp/plates.arpcentral.net`; `netlify.toml` publishes the repo root and adds a
`/privacy` redirect plus caching headers. Custom domain: plates.arpcentral.net.

To regenerate the feature graphic, run `store/feature-graphic.py` in the Android repo and copy the
result to `images/feature-graphic.png`.
