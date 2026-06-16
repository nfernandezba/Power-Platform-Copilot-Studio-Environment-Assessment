# Testing

## Test mode

Use either query string:

```text
?test=1
?mode=test
```

Expected behaviour:

- The assessment is completed automatically.
- The results screen is displayed.
- Dynamic PDF generation remains available.
- The packaged sample report can be downloaded.
- The CoE Toolkit carousel contains the four configured tools.

## Evidence files

- `tests/static-validation.json`: structure, translations, version and asset checks.
- `tests/browser-flow-results.json`: desktop and mobile test-mode flows.
- `tests/sample-download-results.json`: packaged PDF availability and signature check.

## Browser execution note

The package includes a static browser-flow contract result. Chromium navigation could not be executed in the artifact sandbox because it is blocked by administrator policy. Repeat the documented test-mode flow after GitHub Pages deployment.
