# C152 & C172 Engine Explorer

An interactive 3D study model of the Lycoming engines in the Cessna 152 (O-235-L2C), 172P (O-320-D2J) and 172S (IO-360-L2A).

- **Explore**: orbit the engine and click any part for what it is, how it works and pilot's notes. Includes X-ray, section cuts, air/fuel/exhaust/oil flow, an exploded view, and parts you can pull off by hand.
- **Run-up**: a run-up simulator with gauges, magneto checks, carb heat, engine sound and practice faults to diagnose.
- **Teardown**: a 17-step guided teardown in a mechanic's order, from the propeller to the crankshaft.

The whole site is one file, `index.html`. It loads three.js from jsDelivr and fonts from Google Fonts, so there is nothing to build.

## Publish on GitHub Pages

1. Push this repository to GitHub with `index.html` at the root of the `main` branch.
2. On GitHub, open the repository's **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

The empty `.nojekyll` file tells GitHub Pages to publish the files as they are, without running Jekyll. Pages is free for public repositories; a private repository needs a paid GitHub plan.

## Run it locally

Open `index.html` in a browser. It needs an internet connection for three.js and the fonts.

---

For study only. Figures come from Lycoming manuals and data sheets and from Cessna POH and checklist extracts; the POH for the specific airplane always governs.
