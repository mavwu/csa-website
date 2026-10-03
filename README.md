# Climate-Smart Agriculture showcase

A static showcase for an Android Flutter agriculture prototype, with feature explanations and application screenshots.

## Status and scope

The active crop-suggestion logic is an experimental local CSV comparison. Historical Python/ML files do not establish a deployed ML engine or validated agricultural advice.

## Run or evaluate

Run a static server from the repository root:

```sh
python -m http.server 4173
```

Open `http://localhost:4173` and select the relevant HTML page or variant directory. No build step is required for plain HTML/CSS/JavaScript. Use a server when scripts fetch local content; opening a file directly can produce different behavior.

## Example workflow

Compare each feature statement with the associated mobile screen and confirm screenshot alt text and mobile layout.

## Checks

No meaningful automated application check was established from the reviewed manifest. Evaluate the walkthrough with synthetic data and record the commit, environment, and result. For a static site, inspect narrow/wide layouts, keyboard focus, links, forms, and console errors.

## Implementation notes

See the [implementation guide](docs/PROJECT_GUIDE.md) for the code map, configuration boundary, and evidence to capture for a case study.
