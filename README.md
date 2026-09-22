# tectonic.arpcentral.net

Static website for **Plates**, the road-trip licence plate game for Android.

- `index.html` – homepage, using the Play Store feature graphic
- `privacy.html` – privacy policy for the Play Store listing
- `images/` – feature graphic, icons, and screenshots copied from the Android app's `store/` and `art/` folders

Plain HTML and CSS with no build step. Intended for GitHub Pages: `CNAME` points the site at
tectonic.arpcentral.net and `.nojekyll` disables Jekyll processing.

To regenerate the feature graphic, run `store/feature-graphic.py` in the Android repo and copy the
result to `images/feature-graphic.png`.
