# TabuMap – site

Public landing page, privacy policy, terms and third-party notices for TabuMap, served by GitHub Pages.
TabuMap finds the land block (gush) and parcel (helka) you are standing on, by GPS or search, from the Survey of
Israel's open parcel layer. A private initiative by RabieMan Labs – not a government service.

The app code and data pipeline live in the private repo `RabieMan/tabumap-app`. This repo holds only what must be public.

**Status:** in development · app v0.4.1 · coming soon to Google Play

- Home: https://rabieman.github.io/tabumap-site/
- Privacy policy: https://rabieman.github.io/tabumap-site/privacy.html
- Terms of use: https://rabieman.github.io/tabumap-site/terms.html
- Third-party notices: https://rabieman.github.io/tabumap-site/licenses.html
- Studio home page: https://rabieman.github.io/ (TabuMap card, tagged "in development")

## Contents (`main`)

| File | What it is |
| --- | --- |
| `index.html` | Landing page in the RabieMan Labs / AutoPedia template: hero, screenshots, feature cards (Hebrew, then English) |
| `privacy.html` | Privacy policy (he/en): no sign-up, location used on the device only, external services listed (incl. the Street View link) |
| `terms.html` | Terms of use (he/en): not professional advice, boundaries are illustrative, data accuracy, liability |
| `licenses.html` | Third-party notices: MapLibre GL, PMTiles, mapbox-gl-rtl-text, Survey of Israel data, OpenFreeMap/OSM, Esri |
| `img/` | App icon, RabieMan Labs logo, screenshots (`01-gush-he.jpg`, `02-parcel-he.jpg`, `03-gps-he.jpg`) |
| `.github/workflows/publish-landing.yml` | Copies landing edits from `main` into `gh-pages` |

Features listed on the landing page: GPS parcel lookup with nearby-parcel warning, block/parcel search, parcel card,
map and satellite, Street View button; marked "soon": zoning plans and a Tabu extract analyzer.

## Branches

- **`main`** – the pages above. Edit here; every push is copied to `gh-pages` within a minute
  (workflow "Publish landing page changes").
- **`gh-pages`** – what Pages serves. Rebuilt by `tabumap-app` on demand and on the 3rd of every month:
  landing from `main` at the root, the web beta under `/app/`, parcel data under `/app/data/`.
  Force-pushed as a single commit, so the repo does not grow. **Do not edit it by hand** – it is overwritten on every build.

The web beta at `/app/` is for testing only and is not linked from the landing page.

## Contact

rabieman.labs+tabumap@gmail.com
