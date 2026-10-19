# Publish the repaired quiz

1. Open the GitHub repository that publishes brianbays.com.
2. Open its world-capitals-quiz folder (the folder containing the current index.html).
3. Choose Add file > Upload files.
4. Upload index.html, countries.json, and DATA-LICENSE.txt from this folder, replacing index.html.
5. Commit to the branch your website deploys from, then wait for GitHub Pages deployment to finish.
6. Open https://brianbays.com/world-capitals-quiz/ and hard-refresh (Ctrl+Shift+R).

The quiz data is embedded in index.html; no API key or build step is required.
Keep countries.json and DATA-LICENSE.txt alongside it for dataset attribution and redistribution.
The maps still use external map services. Pins use country coordinates.

Data source: https://github.com/mledoze/countries
License: Open Database License, included in DATA-LICENSE.txt.
The bundled dataset is filtered to entries with capitals and transformed to quiz fields.
Existing quiz alternate answers are retained. This repair is not a full editorial audit of those answers.

Verified: JavaScript syntax, loading, question 1 of 10, multiple-choice answer scoring,
advancement to question 2, and no browser JavaScript errors in that flow.

live-quiz.html is the untouched original downloaded from the live site.
