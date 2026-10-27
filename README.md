# PSC PZero projects
[![DOI](https://zenodo.org/badge/1435575315.svg)](https://doi.org/10.5281/zenodo.23688323)

Supporting projects for the Piecewise Structural Complex manuscript submitted to [Solid Earth](https://www.solid-earth.net/home.html).


## Open the projects

Open the `.p0` files in [PZero](https://github.com/gecos-lab/PZero). Keep each corresponding `_p0/` folder beside its project file.

- **Synthetic sections:** [Synthetic_paper.p0](Sections/Synthetic_paper.p0)
- **Synthetic 3D:** [3DSynthetic_paper.p0](Synthetic3D/3DSynthetic_paper.p0)
- **Llyn Padarn:** [LlynPadarn_paper.p0](LlynPadarn/LlynPadarn_paper.p0)
- **Utah FORGE:** [Utah_paper.p0](UtahFORGE/Utah_paper.p0)

## PyMeshIt projects

Open the `.pmit` files in PyMeshIt for loading already processed meshes.

- **Synthetic 3D:** [3DSynthetic_paper_PMI.pmit](Synthetic3D/3DSynthetic_paper_PMI.pmit)
- **Llyn Padarn:** [LlynPadarn_paper.pmit](LlynPadarn/LlynPadarn_paper.pmit)
- **Utah FORGE:** [Utah_paper.pmit](UtahFORGE/Utah_paper.pmit)


## Data sources and licences

### Llyn Padarn

The Llyn Padarn example is a simplified geological model inspired by the British Geological Survey’s [Llyn Padarn (S&D), 1:25,000 Classical Areas Map (1988)](https://shop.bgs.ac.uk/Shop/Product/BSP_CA38C).

Topography is derived from [EU-DEM v1.1 (European Environment Agency, 2016)](https://sdi.eea.europa.eu/catalogue/srv/api/records/3473589f-0854-4601-919e-2e7dd172ff50), provided by the Copernicus Land Monitoring Service under its full, free and open access terms. The elevation data have been adapted for geological modelling. No endorsement by the European Union is implied.

BGS source material remains subject to [BGS copyright and licensing terms](https://www.bgs.ac.uk/bgs-intellectual-property-rights/using-bgs-copyright-material/).

It is also based on the established [PZero Llyn Padarn test project](https://github.com/gecos-lab/PZero-test-Llyn-Padarn), developed by Andrea Bistacchi for teaching and testing, and adapted here for the STM–PSC workflow.

### Utah FORGE

The Utah example uses data adapted from:

Podgorney, R. (2020). *Utah FORGE: Data for 3-D Model Development—Lithology, Temperature, Pressure, and Stress*. Idaho National Laboratory. https://doi.org/10.15121/1605155.

The source dataset is distributed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The data have been adapted for geological modelling in PZero.

We acknowledge the [Utah FORGE project](https://utahforge.com/) and the U.S. Department of Energy for making these data available. No endorsement by the original data providers is implied.
