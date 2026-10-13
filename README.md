# Schrödinger's Navigator — Project Website

This repository hosts the project page for **Schrödinger's Navigator: Imagining an Ensemble of Futures for Zero-Shot Object Navigation**.

- Website: https://heyu322.github.io/Schrodinger-Navigator.github.io/
- arXiv preprint: https://arxiv.org/abs/2512.21201
- The project's author affiliations, method descriptions, and numerical results on this site are synchronized with the **CoRL 2026 camera-ready manuscript** (October 13, 2026).
- The arXiv preprint linked from the website may contain older results. The website's results follow the camera-ready manuscript.

## Results

HM3D ObjectNav: **SR 0.682**, **SPL 0.311**, **DTG 1.84 m**. Unitree Go2 controlled evaluation against an InstructNav-style baseline: static search **23/30 vs. 22/30** and occlusion-heavy search **17/30 vs. 11/30**. The website also mirrors the manuscript's occlusion-severity and FAVM ablation tables.

The left, right, and overhead candidate trajectories are virtual camera viewpoints for future imagination, **not robot-executed paths**. The method uses risk-aware waypoint ranking, without claiming formal safety guarantees or validated dynamic-obstacle benchmark performance.

## Attribution and license

The site is adapted from the [Nerfies website template](https://github.com/nerfies/nerfies.github.io). Template credit and the original [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) notice are preserved. Other paper content and media retain their applicable rights.
