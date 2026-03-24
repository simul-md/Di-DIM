# Excited Argon Cluster Data: Di-DIM Geometries, Energies and PECs

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains data associated with the publication:

> Mukul Dhiman and Benoit Gervais,
> "Correcting Rydberg Excitations in Argon Clusters: From Trimer to Excimer Localization",
> *Chemical Physics Letters*, 2026, [DOI]

## Contents

### `geometries/`
Optimized lowest-energy isomer geometries of ArN* clusters (N = 3–25, 55–57)
in the lowest triplet Rydberg state (3p⁵4s configuration), obtained using
the Di-DIM method. Files are in standard `.xyz` format (Angstroms).

### `PECs/`
Ar₂* dimer potential energy curves used to parametrize the Di-DIM Hamiltonian:
- Adiabatic HPP curves
- Diabatic Di-DIM curves (after diabatisation)
- Ad hoc 3p4p state used for avoided crossing correction

## Units
- Geometries: xyz format and in atomic units (au)
- Energies: atomic units (au) and cm⁻¹ as indicated in each file header
- PEC radius: atomic units (au)

## Usage

Each subfolder contains its own `README.md` with column descriptions.

Geometries can be visualized with any standard molecular viewer
(e.g. VESTA, Avogadro, VMD, ASE).

## Citation

If you use this data, please cite:

## License

This dataset is licensed under
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
You are free to share and adapt the data, provided appropriate credit is given.

## Contact

Mukul Dhiman 
Benoit Gervais
