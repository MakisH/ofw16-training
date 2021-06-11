# Level 2: Using the OpenFOAM adapter

---

## What does the adapter do?

<img src="images/level2/openfoam_adapter_overview_linking.svg" />

vvv

## What does the adapter do?

<img src="images/level2/openfoam_adapter_overview_data.svg" />

vvv

## What does the adapter do?

<img src="images/level2/openfoam_adapter_overview_checkpointing.svg" />

vvv

## What does the adapter do?

<img src="images/level2/openfoam_adapter_overview_timestep.svg" />

---

## Dependencies

- [preCICE](https://precice.org/installation-overview.html) v2 (e.g. [packages for Ubuntu](https://github.com/precice/precice/releases))
- Recent OpenFOAM (e.g. v1706-v2012 or 4-8)
- [OpenFOAM-preCICE adapter](https://github.com/precice/openfoam-adapter) v1.0 (for your OpenFOAM)

---

## Building

```bash
openfoam-adapter/ $ ./Allwmake
```

vvv

<img src="images/level2/openfoam-adapter-building.png" max-height="400"/>

---

## Tutorial: Flow over a heated plate

![](images/level2/openfoam-openfoam_flat_plate_surface_T_RBG_ruler.png)

<small>Find the tutorial on <a href="https://precice.org/tutorials-flow-over-heated-plate.html">precice.org/tutorials-flow-over-heated-plate.html</a>.</small>

---

## Configuration: overview

![](images/level2/config.svg)

vvv

## Configuration: files

<pre><code class="language-bash" data-trim data-line-numbers="|3, 4, 10, 14, 19, 20, 26, 30">
.
├── clean-tutorial.sh
├── fluid-openfoam
│   ├── 0/
│   ├── clean.sh
│   ├── constant/
│   ├── run.sh
│   └── system
│       ├── blockMeshDict
│       ├── controlDict
│       ├── decomposeParDict
│       ├── fvSchemes
│       ├── fvSolution
│       └── preciceDict
├── precice-config.xml
├── README.md
├── solid-fenics/
├── solid-nutils/
└── solid-openfoam
    ├── 0/
    ├── clean.sh
    ├── constant/
    ├── run.sh
    └── system
        ├── blockMeshDict
        ├── controlDict
        ├── decomposeParDict
        ├── fvSchemes
        ├── fvSolution
        └── preciceDict


</code></pre>

<!-- Continuing in index.html -->
