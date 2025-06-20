---
title: "Parallel Quantum Chemistry on Noisy Quantum Computers"
description: "Quantum-classical algorithm running on (real) quantum hardware"
date: "01.01.2016"
# demoURL: "https://astro-sphere-demo.vercel.app"
# repoURL: "https://github.com/markhorn-dev/astro-sphere"
---

<!-- <img src="/projects/sdwscales.png" width=50% class="my-10"> -->
<img src="/projects/quantumcircuit.svg" width=100% class="my-10 p-10 bg-stone-200 border border-black rounded-lg">
<!-- <img src="/projects/sdwpd.png" width=100% class="my-10"> -->

<!-- #### Partners -->

#### TLDR

This work introduces a parallel quantum-classical algorithm for computing molecular ground-state energies, designed to run efficiently on today’s quantum hardware. The method, demonstrated on IBM quantum computers, enables scalable simulations by splitting the problem into smaller, independently solvable parts.

#### Partners

<div style="display: flex; align-items: center; gap: 1rem;">
  <img src="/logos/pc2.svg" class="dark:invert" width="22%">
  <img src="/logos/nhr.svg" class="dark:invert" width="12%">
</div>

#### Abstract

A parallel hybrid quantum-classical algorithm for the solution of the quantum-chemical ground-state energy problem on gate-based quantum computers is presented. This approach is based on the reduced density-matrix functional theory (RDMFT) formulation of the electronic structure problem. For that purpose, the density-matrix functional of the full system is decomposed into an indirectly coupled sum of density-matrix functionals for all its subsystems using the adaptive cluster approximation to RDMFT. The approximations involved in the decomposition and the adaptive cluster approximation itself can be systematically converged to the exact result. The solutions for the density-matrix functionals of the effective subsystems involves a constrained minimization over many-particle states that are approximated by parametrized trial states on the quantum computer similarly to the variational quantum eigensolver. The independence of the density-matrix functionals of the effective subsystems introduces a new level of parallelization and allows for the computational treatment of much larger molecules on a quantum computer with a given qubit count. In addition, for the proposed algorithm techniques are presented to reduce the qubit count, the number of quantum programs, as well as its depth. The evaluation of a density-matrix functional as the essential part of our approach is demonstrated for Hubbard-like systems on IBM quantum computers based on superconducting transmon qubits.

#### Resources

- Paper: https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.4.033160
- Code: https://github.com/pc2/rdmft_on_qc