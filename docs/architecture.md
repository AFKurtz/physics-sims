# Architecture

## Purpose

This document describes the software architecture of **Physics Sims**.  
Its purpose is to explain how the project is organized, how major components interact, and how new simulations can be added while keeping the codebase modular and maintainable. Updates will as code is developed.

---

## Design Goals

The architecture is designed around the following goals:

- **Modularity**  
  Each simulation should be implemented as an independent module.

- **Separation of Concerns**  
  Physics logic, rendering, and user interaction should remain separate.

- **Reusability**  
  Shared utilities such as vector math, constants, and numerical integrators should live in common modules.

- **Extensibility**  
  New simulations should be easy to add without major changes to the rest of the system.

- **Performance**  
  Core simulation logic is written in C++ with efficiency in mind.

---

## Structure

The repository is currently organized into the following major components:

```text
PHYSICS-SIMS/
├── core/
├── docs/
│   └── physics/
│       ├── black_hole/
│       │   └── black_hole_concepts.md
│       ├── electron_cloud/
│       │   └── electron_orbital_concepts.md
│       ├── nucleus/
│       │   └── atomic_nucleus_concepts.md
│       ├── architecture.md
│       └── overview.md
├── interface/
├── notebooks/
├── sims/
├── tests/
├── visualization/
└── README.md
```

