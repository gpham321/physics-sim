# Giuse's Physics 25 Simulations

Interactive browser demos for modern physics topics — built as static HTML + vanilla JavaScript, no build step required. Hosted on GitHub Pages.

## Live site

Once Pages is enabled, the site will be available at:

    https://gpham321.github.io/physics-sim/

## What's inside

Pages are listed roughly in the order they come up in Physics 25 (Modern Physics).

| File | Topic |
|------|-------|
| `index.html` | Landing page linking to every simulation and the study guides |
| `simultaneity.html` | Relativity of simultaneity — the spaceship duel; same events as seen by Alice/Bob (in-frame) and Eve (Earth) at v = 0.995 c |
| `relativistic_velocity_addition.html` | Relativistic velocity addition — four animated cases of `u = (u'+v)/(1+u'v/c²)` and its inverse |
| `relativity_momentum.html` | Relativistic momentum and center of mass — two spaceships exchange a photon; shows why `γmv` is needed for total momentum to stay conserved |
| `thermal_radiation.html` | Stefan–Boltzmann, Wien, Planck — why hot things glow, and the ultraviolet catastrophe |
| `photoelectric.html` | Photoelectric effect — light frequency, intensity, cathode material, stopping voltage, I–V curve, and the KE vs. f threshold plot |
| `double_slit.html` | Double-slit and multi-slit interference with three demos: vary λ &amp; slit separation d, vary slit width a, vary number of slits N (up to a 20-slit grating). Top-down wave field + sideways intensity profile with `d sin θ = m λ` fringe markers |
| `uncertainty.html` | Heisenberg's uncertainty principle in three demos: single-slit diffraction (Δx·Δp_y), Gaussian wavepacket Fourier pair (position vs. momentum), and excited-state lifetime ↔ Lorentzian linewidth (ΔE·Δt) |
| `electron_diffraction.html` | Davisson–Germer and Bragg — drag the movable detector along the arc, watch the I(θ) plot light up around the famous 50° peak; flip between constructive and destructive Bragg orders |
| `bohr_model.html` | Interactive Bohr atom — fire photons of variable wavelength, watch the electron absorb and jump up, then spontaneously emit and drop down. Switch between H, He⁺, Li²⁺ and see the transition table light up the matched line |
| `particle_in_a_box.html` | Particle in a 1-D, 2-D and 3-D infinite-square-well box — slide the quantum number(s); displays ψₙ and \|ψₙ\|² (1-D), diverging/sequential heatmaps (2-D), and orthogonal xy/xz/yz slice planes (3-D) |
| `orbitals.html` | Atomic orbitals and electron configuration — four-quantum-number picker (n, ℓ, m_ℓ, m_s), s/p/d/f/g shape gallery, Madelung diagonal, interactive periodic table with element info, multiple orbital-diagram styles (spdf notation, noble-gas shorthand, box diagram, energy-level diagram) |
| `light_and_matter.html` | Light and matter, lasers — three fundamental processes (absorption / spontaneous / stimulated emission) with animated demos, then six tabs (incandescent, discharge, fluorescent, phosphorescent, laser, LED) plus a broadband-vs-lines summary. Includes deep coverage of why 2-level lasers fail, the 3- and 4-level fixes, decay-path control in phosphors, and animated pump → metastable → lase cycles |
| `physics_21_study_guide.html` | Physics 21 (Mechanics &amp; Fluids) full-course study guide — OpenStax College Physics 2e Ch. 1–12, all 19 lectures, both midterms, final review |
| `physics_23_study_guide.html` | Full Physics 23 study guide covering Giancoli chapters 16–25 (lectures 1A–10B) |
| `physics_25_study_guide.html` | Physics 25 (Modern Physics) full-course study guide — OpenStax Ch. 28–30 plus instructor materials, all 19 lectures, both midterms, final review |
| `brain_lab.html` | **Hidden** — Giuse Pham Enterprises Brain Cell Reclamation Lab. Cryo-canister, pink-cell transport tube, golden-ticket payout, pressure gauges, live brain-cell counter. Reachable by clicking "Giuse Pham Enterprises" in the index footer. |
| `images/president_giuse.jpg` | Portrait shown in the top-right corner of every page (and favicon / link preview) |
| `images/giuse_brain.png` | The brain-in-a-jar render used inside the canister on `brain_lab.html` |

## Enabling GitHub Pages

1. Push this repo to GitHub.
2. Open the repo's **Settings → Pages**.
3. Under **Source**, pick **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save. The URL will appear at the top of the Pages settings after a short delay.

## Running locally

Just open `index.html` in a browser. No server needed.

The brain lab page (`brain_lab.html`) keeps a daily redemption counter in `localStorage` and tries to fetch your public IP from `api.ipify.org` to share the per-day cap across browsers on the same network. If the fetch is blocked it falls back to a stable device-fingerprint hash. Both paths are best-effort client-side — fully resetting localStorage will reset the counter.

---

Giuse Pham Enterprises — Est. 2026
