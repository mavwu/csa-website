# Climate-Smart Agriculture showcase: implementation guide

A static showcase for an Android Flutter agriculture prototype, with feature explanations and application screenshots.

## Scope

**Repository role:** Project showcase.

The active crop-suggestion logic is an experimental local CSV comparison. Historical Python/ML files do not establish a deployed ML engine or validated agricultural advice.

## Local evaluation

Run a static server from the repository root:

```sh
python -m http.server 4173
```

Open `http://localhost:4173` and select the relevant HTML page or variant directory. No build step is required for plain HTML/CSS/JavaScript. Use a server when scripts fetch local content; opening a file directly can produce different behavior.

## Code map

| Path | Responsibility |
| --- | --- |
| `assets` | Images and bundled data |
| `index.html` | Page or browser application entry |
| `styles.css` | Presentation and responsive styles |

## Walkthrough

Compare each feature statement with the associated mobile screen and confirm screenshot alt text and mobile layout.

## Verification

No meaningful automated application check was established from the reviewed manifest. Evaluate the walkthrough with synthetic data and record the commit, environment, and result. For a static site, inspect narrow/wide layouts, keyboard focus, links, forms, and console errors.

## Evidence for a case study

Describe this repository as a **project showcase**. A useful case study explains the problem above, traces the walkthrough to its source, names a concrete implementation decision, and records a repeatable evaluation. Separate implemented behavior from roadmap work. Capture screenshots using synthetic data and identify the demonstrated commit.
