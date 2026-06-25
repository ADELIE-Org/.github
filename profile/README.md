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
| [CartesianGeometry.jl](https://github.com/ADELIE-org/CartesianGeometry.jl) | Cut-cell moment router — volume fractions, apertures, and staggered moments on Cartesian grids |
| [Vofinit.jl](https://github.com/ADELIE-org/Vofinit.jl) | VOF initialisation — exact volume fractions from an implicit interface |
| [VofiJul.jl](https://github.com/ADELIE-org/VofiJul.jl) | Pure-Julia VOFI — volume fractions, moments, and adjoints in 1–4D |
| [VOFTools.jl](https://github.com/ADELIE-org/VOFTools.jl) | Geometrical VOF tools — polygon/polyhedron truncation and PLIC reconstruction |
| [isoap.jl](https://github.com/ADELIE-org/isoap.jl) | Isosurface extraction on arbitrary polyhedra and grids |
| [FrontIntrinsicOps.jl](https://github.com/ADELIE-org/FrontIntrinsicOps.jl) | Intrinsic differential operators on fronts and interfaces |
| [FrontCartesianGeometry.jl](https://github.com/ADELIE-org/FrontCartesianGeometry.jl) | Cartesian front-tracking geometry primitives |

## External packages

| Package | Description |
|---------|-------------|
| [ImplicitIntegration.jl](https://github.com/ELallinec/ImplicitIntegration.jl) | Numerical integration over implicitly-defined domains and surfaces |

---

*ADELIE is named after the Adélie penguin — an animal that lives at the sharpest interface on Earth.*
