# Vaggelis Gkouzelos – Portfolio

Static site: one `index.html` plus the `assets/` folder. No build step.

## What is in `assets/`
- `CV_Gkouzelos_Vaggelis.pdf` – the file behind the "Download CV" button (replace it to update the CV).
- `three.min.js` – the 3D library used by the solar park on the pv-forecast card (three.js r128, local copy).
- `medintake-workflow.jpg` – screenshot of the n8n workflow.
- `solar-placeholder.svg` – shown only if the visitor's browser has no WebGL.

## Customise
- **Colours / fonts:** CSS variables at the top of `index.html` (section "1. THEME"), dark and light.
- **Greek text:** every translated element has a `data-el="…"` attribute next to its English text.
- **3D park:** the `PARK` object and `updateCamera()` in section D of the script.

## Deploy
- **GitHub Pages:** push this folder to a repo → Settings → Pages → deploy from branch (root).
- **Netlify:** drag and drop the folder at app.netlify.com/drop.
- **Vercel:** `vercel` in this folder, or import the repo (framework preset: Other).
