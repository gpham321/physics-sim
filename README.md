# Giuse's Physics 25 Simulations

Interactive browser demos for modern physics topics — built as static HTML + vanilla JavaScript, no build step required. Hosted on GitHub Pages.

## Live site

Once Pages is enabled, the site will be available at:

    https://gpham321.github.io/physics-sim/

## What's inside

| File | Topic |
|------|-------|
| `index.html` | Landing page linking to every simulation and the study guide |
| `photoelectric.html` | Photoelectric effect — light frequency, intensity, cathode material, stopping voltage, I–V curve, and the KE vs. f threshold plot |
| `relativity_momentum.html` | Relativistic momentum and center of mass — two spaceships and a photon |
| `relativistic_velocity_addition.html` | Relativistic velocity addition — four animated cases of `u = (u'+v)/(1+u'v/c²)` and its inverse |
| `simultaneity.html` | Relativity of simultaneity — the spaceship duel |
| `thermal_radiation.html` | Stefan–Boltzmann, Wien, Planck — why hot things glow, and the ultraviolet catastrophe |
| `bohr_model.html` | Interactive Bohr atom — fire photons of variable wavelength, watch the electron absorb and jump up, then spontaneously emit and drop down. Switch between H, He⁺, Li²⁺ and see the transition table light up the matched line |
| `double_slit.html` | Double-slit and multi-slit interference with three demos: vary λ &amp; slit separation d, vary slit width a, vary number of slits N (up to a 20-slit grating). Top-down wave field + sideways intensity profile with `d sin θ = m λ` fringe markers |
| `uncertainty.html` | Heisenberg's uncertainty principle in three demos: single-slit diffraction (Δx·Δp_y), Gaussian wavepacket Fourier pair (position vs. momentum), and excited-state lifetime ↔ Lorentzian linewidth (ΔE·Δt) |
| `physics_21_study_guide.html` | Physics 21 (Mechanics &amp; Fluids) full-course study guide — OpenStax College Physics 2e Ch. 1–12, all 19 lectures, both midterms, final review |
| `physics_23_study_guide.html` | Full Physics 23 study guide covering Giancoli chapters 16–25 (lectures 1A–10B) |
| `physics_25_study_guide.html` | Physics 25 (Modern Physics) full-course study guide — OpenStax Ch. 28–30 plus instructor materials, all 19 lectures, both midterms, final review |
| `brain_lab.html` | **Hidden** — Giuse Pham Enterprises Brain Cell Reclamation Lab. Cryo-canister, pink-cell transport tube, golden-ticket payout, pressure gauges, live brain-cell counter. Reachable by clicking "Giuse Pham Enterprises" in the index footer. |
| `president_giuse.jpg` | Portrait shown in the top-right corner of every page (and favicon / link preview) |
| `giuse_brain.png` | The brain-in-a-jar render used inside the canister on `brain_lab.html` |

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
