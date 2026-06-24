# ADELIE

**Adaptive Discretization Ecosystem for Liquid–Interface Evolution**

A collection of open-source packages for the numerical simulation of multiphase flows, phase change, and moving interfaces.

---

## What we build

ADELIE packages share a common design philosophy: modular, composable numerical methods that adapt to the geometry and physics of liquid–interface problems.

- **Adaptive methods** — structured mesh refinement, adaptive numerical methods.
- **Discretization** — finite volume, cut-cell, and embedded-boundary schemes with well-defined interfaces between components
- **Multiphase flow** — incompressible two-phase flows with surface tension, phase change, and topology changes
- **Moving interfaces** — level-set, VOF, and hybrid interface-tracking methods

## Design principles

- Packages are independently usable but designed to compose
- Implementations target Julia for performance, expressiveness, and reproducibility
- Each package is tested, documented, and versioned following a shared standard

## Packages

| Package | Description |
|---------|-------------|
| [CartesianGrids.jl](https://github.com/ADELIE-org/CartesianGrids.jl) | Cartesian grid generation and management in arbitrary dimensions |

---

*ADELIE is named after the Adélie penguin — an animal that lives at the sharpest interface on Earth.*
