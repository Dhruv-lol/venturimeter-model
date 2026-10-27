# Venturimeter Model

A standalone interactive venturimeter model for exploring inlet and throat flow conditions. Open `index.html` in a browser or publish the repository with GitHub Pages.

## Features

- Adjustable inlet and throat areas, diffuser angle, inlet velocity, and inlet gauge pressure
- Water and diesel report-reference cases, plus custom fluid density and viscosity
- Ideal Bernoulli and estimated-loss modes
- Commercial-steel Darcy–Weisbach major head loss and editable contraction/diffuser minor-loss coefficients
- Responsive venturi profile and live velocity, pressure, head, and flow outputs

## Model notes

The reported CFD pressures are reference values from the project report. Their negative throat gauge pressures imply negative absolute pressure at standard atmosphere, so they should be treated as reported solver outputs requiring validation. The head-loss estimates use nominal report geometry and assumed transition coefficients; they are not measured CFD losses. See the notes in the app for assumptions and limits.

The app runs entirely in the browser and does not send visitor inputs to a server.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, choose `main` and the `/ (root)` folder, and save.
