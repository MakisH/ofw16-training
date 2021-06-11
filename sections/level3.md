# Level 3: Coupling OpenFOAM with other solvers

---

## Other tutorials

```text [|10-14|42-48]
tutorials
├── elastic-tube-1d
│   ├── fluid-cpp
│   ├── fluid-python
│   ├── solid-cpp
│   └── solid-python
├── elastic-tube-3d
│   ├── fluid-openfoam
│   └── solid-calculix
├── flow-over-heated-plate
│   ├── fluid-openfoam
│   ├── solid-fenics
│   ├── solid-nutils
│   └── solid-openfoam
├── flow-over-heated-plate-nearest-projection
│   ├── fluid-openfoam
│   └── solid-openfoam
├── flow-over-heated-plate-steady-state
│   ├── fluid-openfoam
│   └── solid-codeaster
├── heat-exchanger
│   ├── fluid-inner-openfoam
│   ├── fluid-outer-openfoam
│   └── solid-calculix
├── multiple-perpendicular-flaps
│   ├── fluid-openfoam
│   ├── solid-left-dealii
│   └── solid-right-dealii
├── partitioned-elastic-beam
│   ├── dirichlet-calculix
│   └── neumann-calculix
├── partitioned-heat-conduction
│   ├── fenics
│   └── nutils
├── partitioned-heat-conduction-complex
│   └── fenics
├── partitioned-pipe
│   ├── fluid1-openfoam-pimplefoam
│   ├── fluid1-openfoam-sonicliquidfoam
│   ├── fluid2-openfoam-pimplefoam
│   └── fluid2-openfoam-sonicliquidfoam
├── perpendicular-flap
│   ├── fluid-nutils
│   ├── fluid-openfoam
│   ├── fluid-su2
│   ├── solid-calculix
│   ├── solid-dealii
│   └── solid-fenics
├── quickstart
│   ├── fluid-openfoam
│   └── solid-cpp
└── turek-hron-fsi3
    ├── fluid-openfoam
    └── solid-dealii
```

<small>See <a href="https://precice.org/tutorials.html">precice.org/tutorials.html</a>.</small>

---

## Tutorial: Channel with a perpendicular flap

<img src="images/level3/flap_perp.png" style="max-height:400px;"/>

<small>Find this tutorial on <a href="https://precice.org/tutorials-perpendicular-flap.html">precice.org/tutorials-perpendicular-flap.html</a>.</small>

---

## Dependencies

- [preCICE](https://precice.org/installation-overview.html) v2 (e.g. [packages for Ubuntu](https://github.com/precice/precice/releases))
- Recent OpenFOAM (e.g. v1706-v2012 or 4-8)
- [OpenFOAM-preCICE adapter](https://github.com/precice/openfoam-adapter) v1.0
- [deal.II](https://www.dealii.org/) v9.2
- [deal.II-preCICE adapter/example](https://github.com/precice/dealii-adapter)
