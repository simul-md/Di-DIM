# Excited Argon Cluster Data: Di-DIM Geometries, Energies and PECs

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains data associated with the publication:

> Mukul Dhiman and Benoit Gervais,
> "Correcting Rydberg Excitations in Argon Clusters: From Trimer to Excimer Localization",
> *Chemical Physics Letters*, [Year], [DOI]

## Contents

### `geometries/`
Optimized lowest-energy isomer geometries of ArN* clusters (N = 3–25, 55–57)
in the lowest triplet Rydberg state (3p⁵4s configuration), obtained using
the Di-DIM method. Files are in standard `.xyz` format (Angstroms).

### `energies/`
- `dissociation_energies.csv`: Di-DIM and HPP dissociation energies (cm⁻¹)
  for all cluster sizes, as reported in Table 1 of the manuscript.
- `isomer_energies.csv`: Total energies (au) of lowest isomers per cluster size.

### `PECs/`
Ar₂* dimer potential energy curves used to parametrize the Di-DIM Hamiltonian:
- Adiabatic HPP curves
- Diabatic Di-DIM curves (after diabatisation)
- Ad hoc 3p4p state used for avoided crossing correction

### `hole_populations/`
Atomic hole populations derived from Di-DIM expansion coefficients for each
cluster size, quantifying the spatial character of the excitation.

## Units
- Geometries: Angstroms (xyz format) or atomic units (au) as specified
- Energies: atomic units (au) and cm⁻¹ as indicated in each file header
- PEC radius: atomic units (au)

## Usage

Each subfolder contains its own `README.md` with column descriptions.
Data can be loaded directly with Python:

```python
import pandas as pd
df = pd.read_csv('energies/dissociation_energies.csv')
```

Geometries can be visualized with any standard molecular viewer
(e.g. VESTA, Avogadro, VMD, ASE).

## Citation

If you use this data, please cite:
