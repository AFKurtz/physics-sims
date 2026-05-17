# Overview

## Introduction

**Physics Sims** is a modular C++ simulation framework designed to model and visualize physical systems across multiple domains, including astrophysics, quantum systems, and nuclear physics.

The project combines:

- High-performance numerical simulation (C++)
- A command-line interface (CLI) for control and interaction
- A graphical visualization layer for real-time rendering

The goal is to create a unified environment where different physical systems can be explored, compared, and extended within a consistent architecture.

---

## Project Goals

This project is built with the following goals:

- Develop a **high-performance simulation engine** in C++
- Support **multiple physical domains** within a single framework
- Maintain a **modular and extensible architecture**
- Provide **interactive control via CLI**
- Enable **real-time visualization** of physical systems
- Clearly document the **physics and assumptions** behind each simulation

---

## Simulations

The framework is designed to support multiple simulations, each implemented as a modular component.

### Black Hole Simulation
Models particle motion in a gravitational field, including orbital dynamics and energy behavior. Future extensions may include relativistic effects.

### Electron Cloud Simulation
Visualizes electron probability distributions using quantum-inspired models. Focuses on representing orbitals and density distributions rather than classical trajectories.

### Nucleus Simulation
Explores simplified models of nuclear structure using particle-based or potential-based approaches to represent nucleon interactions.

---

## Architecture Overview

The project is structured into several major components:

- **Core**
  - Shared math utilities, constants, and numerical methods
- **Simulations**
  - Independent physics modules for each system
- **Visualization**
  - Rendering engine for displaying simulation state
- **Interface**
  - CLI-based control system
- **Tests**
  - Validation and correctness checks

Each simulation produces a **state** that is:

1. Updated by the simulation logic
2. Rendered by the visualization system
3. Controlled via the CLI

This separation allows simulations to remain independent while sharing infrastructure.

---

## Design Philosophy

This project follows several guiding principles:

### Modularity
Each simulation is self-contained and interacts with the rest of the system through well-defined interfaces.

### Separation of Concerns
Physics, rendering, and user interaction are handled by separate components.

### Transparency
All physical models, equations, and assumptions are documented.

### Iterative Development
The project is expected to evolve over time, with increasing physical accuracy and improved visualization techniques.

---

## Scope and Limitations

This project is not intended to be a fully accurate scientific solver for all physical systems. Instead, it aims to:

- Provide **educational and exploratory simulations**
- Demonstrate **numerical methods and modeling techniques**
- Balance **physical realism with computational feasibility**

Each simulation documents its own assumptions and limitations in detail.

---


## Related Documentation

- `architecture.md` — detailed system design
- `build_and_run.md` — setup and usage instructions
- `physics/` — equations and models for each simulation
- `notebooks/` — derivations and experimental validation