# TabuMap – site

Public landing page, privacy policy and terms for TabuMap, served by GitHub Pages.
The app code and data pipeline live in the private repo `RabieMan/tabumap-app`.

- Home: https://rabieman.github.io/tabumap-site/
- Web beta: https://rabieman.github.io/tabumap-site/app/
- Privacy policy: https://rabieman.github.io/tabumap-site/privacy.html
- Terms of use: https://rabieman.github.io/tabumap-site/terms.html

## Branches

- **`main`** – the landing pages (`index.html`, `privacy.html`, `terms.html`, `licenses.html`, `img/`). Edit here;
  changes are copied to `gh-pages` automatically (workflow "Publish landing page changes").
- **`gh-pages`** – what Pages serves. Rebuilt about monthly by `tabumap-app` (app under `/app/`, parcel data under
  `/app/data/`). Do not edit it by hand – it is overwritten on every build.
