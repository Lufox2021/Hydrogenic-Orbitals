# Hydrogenic Orbitals

An interactive 3D viewer for hydrogen-atom (one-electron) wavefunctions, built
for chemistry students to explore.

- Pick any n = 1–6 and any s/p/d subshell
- Rotate/zoom the exact analytic orbital
- Toggle between a solid isosurface ("contour") view and a |ψ|² probability
  point-cloud view, with a slider for the isosurface threshold
- Axes labeled in units of the Bohr radius (a₀)
- Radial distribution function chart and node counts for each orbital

Everything is exact analytic hydrogenic wavefunctions (real spherical
harmonics × associated Laguerre radial functions), computed client-side in
the browser — no server, no external data.

## Running it

Just open `index.html` in a browser, or, once GitHub Pages is turned on for
this repo (Settings → Pages → Deploy from branch → `main` / `/ (root)`),
visit the Pages URL.

## Tech

Single self-contained HTML file. 3D rendering via [Three.js](https://threejs.org/)
(loaded from cdnjs).
