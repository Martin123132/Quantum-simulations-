# Quantum Simulations Collection

This repository is a grab‑bag of small, single‑file Python simulations exploring quantum and condensed‑matter phenomena. Each file is a runnable script (usually importing `numpy` and `matplotlib`) that visualizes a particular idea such as braiding anyons, vortex dynamics, superconductivity effects, or wave‑packet motion. Run any script directly with Python, for example:

```bash
python "Quantum Teleportation Demo."
```

Most scripts produce 2D or 3D plots that illustrate the modeled fields, particles, or trajectories.

## Requirements

* Python 3
* `numpy`
* `matplotlib`

Install dependencies with `pip install -r requirements.txt` if you add one, or install the two libraries directly.

## Contents

The scripts are intentionally standalone. Use the file names below to pick the concept you want to explore.

### Orbital, vortex, and toroidal field simulations
* **3D Quantized Vortex Simulation – 20 Particles**, **3D Vortex: Multi-Particle Quantized Orbits** – Multi-particle vortex orbit visualizations.
* **Quantized Orbital Field Simulation**, **Quantized Orbital Field Simulation 2**, **Quantized Orbital Field Simulation – Continued Evolution**, **Quantized Orbital Simulation – Evolution Code**, **Quantized Orbital Simulation – Smooth Curvature Model** – Variations of quantized orbital field evolution.
* **Quantized Toroidal Vortex Simulation** – Toroidal vortex dynamics.
* **Quantized Vortex Simulation Kit** – General-purpose vortex field generator.
* **Particle Orbital Simulation**, **Particle Forge: Nested Field Shells**, **Outer Shell Particle Trajectory – Continued Evolution**, **Replication Kit: 12-Particle Vortex Interaction Simulation** – Particle orbit tracers with layered or replicated setups.
* **Particle Feedback in Toroidal Field**, **Toroidal Curvature Field – Particle Path Simulation**, **Toroidal Curvature Field with Particle Simulation**, **Toroidal Curvature Simulation – Two Particles**, **vortex curvature field** – Particle motion through toroidal or curved fields.
* **Phase field: initialize with a fractional vortex at**, **INIT PARTICLES IN 2D SPACE** – Helpers for setting initial vortex/particle states.
* **Replication Kit: Wavefront Propagation & Causality** – Wavefront evolution and causality constraints.

### Superconductivity and Josephson effects
* **Abrikosov Vortices in Type II Superconductors**, **Flux Quantization Abrikosov Vortex** – Flux quantization and vortex pinning visuals.
* **Josephson Junction (Supercurrent Across Barrier)** – Josephson tunneling demonstration.
* **super conductors SQUID** – SQUID interference patterns.
* **Superconductor Simulation: Disorder-Order (Critical Transition)**, **Superconductors Simulation: Disorder-Order (Critical Transition)** – Disorder-to-order transitions in superconductors.
* **copper pairing** – Cooper-pair style coupling.

### Anyons, braiding, and topological logic
* **Anyon fractional charge** – Fractionalized anyon phase and memory fields.
* **Double Braid: Chirality-Enhanced Logic Demo**, **Non-Abelian Double Braid with Error Injection & Correction**, **Defect Braiding Simulation**, **Fibonacci braid**, **braid(phase, anyons, order)** – Braiding logic and stability demonstrations.
* **Define Majorana pair (non-Abelian anyons) positions**, **Majorana edge mode topological qubi**, **Topological Superconductor (EdgeSurface States)** – Majorana/topological superconducting qubit layouts.
* **Topological Memory Control (No Braiding)**, **"Topological Memory with  error correction** – Memory encoding without or with error correction.
* **Three Anyon Braiding Universal Non-Abelian Logic Simulation** – Universal gate braiding with three anyons.

### Teleportation, entanglement, and measurement
* **Quantum Teleportation Demo.**, **Three sites for teleportation**, **sites for teleportation** – Lattice-based teleportation/transfer examples.
* **quantum entanglement without spooky action**, **simulate MBT quantum entanglement without spooky action** – Entanglement visualizations inspired by MBT.
* **quantum measurement without collapse**, **memory law:** – Alternative measurement and memory rules.
* **Create a repeated V-pattern for Bell S and Memory**, **depending on alignment of field phase and measurement angle** – Bell-state style alignment experiments.
* **Quantum Hall Edge State** – Edge mode transport illustration.

### Wave packets, barriers, and coherence
* **Wavepacket Evolution with Moving Barrier**, **Barrier profile: dual bumps**, **Barrier: Center and width stay fixed, height oscillates**, **Modulated Barrier Function with Phase Offset** – Time-varying potential barrier experiments.
* **Quantum Tunneling Control System** – Steering tunneling probabilities.
* **Wavepackets**, **standing wave behavior and evolving structures** – General wave-packet propagation and standing-wave behaviors.
* **Combined wavefunction array**, **Calculate coherence (how concentrated the field is)** – Wavefunction combination and coherence metrics.
* **Breathing Seed Function**, **Breathing disnode**, **Breathing seed function (internal MTS curvature seed)**, **Twin Breathing Barriers Coherence Map**, **Mobile Seed Function** – Breathing/oscillating seed patterns and coherence comparisons.
* **Curvature Field Simulation Codes**, **Curved Trajectory Simulation**, **Magnetic Interaction Layer**, **dispatch phase**, **Dispatch resso** – Field curvature, magnetic perturbations, and phase dispatch helpers.
* **Gaussian random fluctuations** – Noise injection for stochastic behaviors.

### Atomic and particle structure models
* **Atomic Simulation Code**, **Atomic Standing Wave Pattern Code**, **Atomic Structure Simulation Code** – Basic atomic orbital and standing-wave sketches.
* **Quantum Resonance Layer – Atom Model** – MBT-inspired atomic shells with resonance layers.
* **Nucleus + Electrons** – Simple nucleus/electron illustration.
* **Quantum Spin Liquid Model** – Spin liquid lattice visualization.
* **Quantum Maze: Double Waves, Scrambling Maze** – Wave interference within maze-like potentials.
* **Magnetic Interaction Layer**, **Particle Feedback in Toroidal Field** – Magnetic or feedback interactions.
* **GLUEBALL DUET  ψ₅ and ψ₆, same phase and speed**, **GLUEBALL DUET — ψ₅ and ψ₆, same phase and speed**, **GLUEBALL DUET (bonded pair from both sides)** – Glueball-style paired wavefunction visualizations.
* **10 MILLION STATIC PARTICLES** – Static particle initialization stress test.

### Miscellaneous experiments and archives
* **EXTREME MULTI-DIMENSIONAL LOCKPICKING LABORATORY**, **MULTIVERSE MATHEMATICAL WARFARE: BEYOND REALITY ARSENAL**, **QUANTUM SINGULARITY BREACH: REALITY-BREAKING ARSENAL** – Conceptual multi-field demonstrations.
* **Quantum Tunneling Control System**, **Quantum Maze: Double Waves, Scrambling Maze** – Quantum control playgrounds.
* **Simulation Code Archive**, **Experimental Implementation Guide** – Reference bundles and implementation notes.
* **superposition** – Simple superposition illustration.

## Usage tips

* Because file names contain spaces and punctuation, wrap them in quotes when running with Python.
* Many scripts render plots; ensure your environment can display or save matplotlib figures.
* The scripts are independent—modify parameters inside each file to explore variations on the physical phenomena.
