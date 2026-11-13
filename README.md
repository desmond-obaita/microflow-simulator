# Two-Phase Microflow Simulator

A browser-based phase-field solver for immiscible laminar two-phase flow (water and cyclohexane by default), set up with COMSOL's *Two-Phase Flow, Phase Field* formulation so the two can be compared.

## What's in this folder

| File | What it is | Do you edit it? |
|---|---|---|
| `index.html` | The website: layout, inputs, plots and the methods write-up. It loads `solver.js`. | Yes, for text, layout, presets and styling |
| `solver.js` | The physics engine: Navier–Stokes and Cahn–Hilliard on a staggered grid. Used by both the website and the tests. | Yes, for the physics and numerics |
| `assets/lab-background.jpg` | Background and banner image | Swap it for another image with the same name |
| `tests/test_poiseuille.js` | Validation: channel flow against the exact parabola | Run it after changing the solver |
| `tests/test_droplets.js` | Validation: Laplace pressure and sessile-drop contact angle | Run it after changing the solver |
| `.nojekyll` | Empty file that tells GitHub Pages to serve the files as they are | No |


