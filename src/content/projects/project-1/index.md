---
title: "Quantum Monte Carlo Simulations of Metallic Quantum Criticality"
description: "Cologne - Stanford - Weizmann"
date: "01.02.2020"
doi: "https://doi.org/10.1103/PhysRevResearch.2.023008"
category: "physics"
---

<!-- <img src="/projects/sdwscales.png" width=50% class="my-10"> -->
<img src="/projects/sdw_figures.png" width=100% class="my-10 bg-white border border-black p-10 rounded-lg">
<!-- <img src="/projects/sdwpd.png" width=100% class="my-10 bg-stone-200 border border-black px-12 py-10 rounded-lg"> -->

#### Summary

Developed the first HPC-ready [quantum Monte Carlo code](https://github.com/carstenbauer/dqmc) in [Julia](https://julialang.org/). Ran large-scale simulations (~10M CPU-core hours, ~80TB of data) on Germany's fastet supercomputer [JUWELS](https://www.fz-juelich.de/en/ias/jsc/systems/supercomputers/juwels). Gained insights into the metallic $O(3)$ symmetric antiferromagnetic quantum critical point and the emergence of high-temperature superconductivity.

#### Resources

[Full Paper](/paper/PhysRevResearch.2.023008.pdf) ⋅
[Code Repository](https://github.com/carstenbauer/dqmc) ⋅
[Talk](/talks/sdwo3.pdf) ⋅
[PhD Thesis](/files/carstenbauer_phd_thesis.pdf) ⋅
[Full Numerics Paper](/paper/SciPostPhysCore_2_2_011.pdf) ⋅
[Numerics Code Repository](https://github.com/carstenbauer/StableDQMC.jl)

#### Partners

<div style="display: flex; align-items: center; gap: 1rem;">
  <img src="/logos/stanford.svg" class="dark:invert" width="20%">
  <img src="/logos/weizmann.svg" class="dark:invert" width="38%">
  <img src="/logos/uoc.svg" class="dark:invert" width="20%">
</div>

<!-- #### Abstract

We present numerically exact results from sign-problem free quantum Monte Carlo simulations for a spin-fermion model near an O(3) symmetric antiferromagnetic (AFM) quantum critical point. We find a hierarchy of energy scales that emerges near the quantum critical point. At high-energy scales, there is a broad regime characterized by Landau-damped order parameter dynamics with dynamical critical exponent 𝑧=2, while the fermionic excitations remain coherent. The quantum critical magnetic fluctuations are well described by Hertz-Millis theory, except for a 𝑇−2 divergence of the static AFM susceptibility. This regime persists down to a lower-energy scale, where the fermions become overdamped and, concomitantly, a transition into a 𝑑-wave superconducting state occurs. These findings resemble earlier results for a spin-fermion model with easy-plane AFM fluctuations of an O(2) spin density wave (SDW) order parameter, despite noticeable differences in the perturbative structure of the two theories. In the O(3) case, perturbative corrections to the spin-fermion vertex are expected to dominate at an additional energy scale, below which the 𝑧=2 behavior breaks down, leading to a novel 𝑧=1 fixed point with emergent local nesting at the hot spots [Schlief et al., Phys. Rev. X 7, 021010 (2017)]. Motivated by this prediction, we also consider a variant of the model where the hot spots are nearly locally nested. Within the available temperature range in our study (𝑇≥𝐸𝐹/200), we find substantial deviations from the 𝑧=2 Hertz-Millis behavior, but no evidence for the predicted 𝑧=1 criticality. -->