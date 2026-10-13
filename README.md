# Schrödinger's Navigator

Project website for **Schrödinger's Navigator: Imagining an Ensemble of Futures for Zero-Shot Object Navigation**.

- Project page: https://heyu322.github.io/Schrodinger-Navigator.github.io/
- Paper: https://arxiv.org/abs/2512.21201

## Overview

Schrödinger's Navigator uses trajectory-conditioned 3D imagination to guide zero-shot object navigation in occlusion-heavy environments. Three complementary virtual camera trajectories—left, right, and overhead—help generate imagined 3D scenes. A Future-Aware Value Map (FAVM) integrates semantic relevance, newly imagined free space, and geometric risk with observation-based guidance to select navigation targets.

## Evaluation

HM3D ObjectNav: **SR 0.682**, **SPL 0.311**, and **DTG 1.84 m**.

Controlled Unitree Go2 evaluations against an InstructNav-style baseline:
- Static object search: **23/30 vs. 22/30**.
- Occlusion-heavy scenarios: **17/30 vs. 11/30**.

The website displays the main simulation and real-world benchmark tables alongside the project teaser, framework, and supplementary video.

## Attribution

The site is adapted from the [Nerfies project-page template](https://github.com/nerfies/nerfies.github.io). Template attribution and the original [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) notice are retained. Other paper content and media remain subject to their applicable rights.
