# Power Platform & Copilot Studio Environment Strategy — Quick Assessment

![Version](https://img.shields.io/badge/version-v1.0-5552B4)
![Deployment](https://img.shields.io/badge/deployment-GitHub%20Pages-3895FF)
![Licence](https://img.shields.io/badge/licence-MIT-FCC004)

Browser-based bilingual assessment for evaluating the definition, coverage, documentation, communication and currency of an organisation's Power Platform and Copilot Studio environment strategy.

## Package layout

```text
/
├── index.html
├── README.md
├── LICENSE
├── .nojekyll
├── TEST-REPORT.md
├── manifest.webmanifest
├── assets/
│   ├── icons/
│   ├── images/
│   │   ├── books/
│   │   └── tools/
│   ├── reports/
│   │   └── Power_Platform_Copilot_Studio_Environment_Strategy_Assessment_Sample_Report_v1.0.pdf
│   ├── vendor/
│   ├── styles.css
│   └── app.js
├── docs/
│   ├── DEPLOYMENT.md
│   └── TESTING.md
└── tests/
    ├── static-validation.json
    ├── browser-flow-results.json
    └── sample-download-results.json
```

## Test mode

Open the deployed URL with `?test=1` or `?mode=test` to load a completed assessment and the report-ready results page.

## Documentation

- [Deployment](docs/DEPLOYMENT.md)
- [Testing and test mode](docs/TESTING.md)
- [Validation evidence](TEST-REPORT.md)

## Licence

MIT. See [LICENSE](LICENSE).
