# Manmeet Singh — Technology Portfolio

A dependency-free, responsive static portfolio for CMPT 3835. No build tools or external JavaScript packages are required. All seven case studies, interactive charts, theme control, and the synthetic cylinder demo run in the browser.

## Publish
1. Extract the ZIP. Upload `index.html`, `style.css`, `app.js`, `assets/` and this README to the root of `manmeets0704.github.io` on the `main` branch. Do not upload the ZIP itself.
2. Create `.github/workflows/deploy.yml` using the included workflow (if browser upload does not preserve hidden folders, use Add file > Create new file and enter that full path). Commit to `main`.
3. In Settings > Pages, select GitHub Actions. In Actions, open the deployment run and confirm it succeeds.
4. Visit https://manmeets0704.github.io/ in an incognito window. Check all case studies, theme switch, filters, resume, and contact links.

## Local preview
Open `index.html` in a browser, or run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publication review
The site excludes original datasets, notebooks, database files, private repository links and credentials. Automotive client identity is anonymized. The gas demo uses fictional values. Aggregate results are drawn from saved academic evidence, not independently retrained. Before committing, verify team-level contribution wording and public sharing rights for coursework and API-derived aggregates. The public resume omits the personal phone number. The photo is cropped from the provided original. No separate project repository is required.
