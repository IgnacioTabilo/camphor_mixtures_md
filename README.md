# Camphor-Based Terpene Mixtures — Molecular Dynamics Files

Supporting data for:

> **Terpene-Based Eutectic Mixtures as Green Solvents for CO₂ Capture: Experimental Characterization and Molecular Insights**

## Overview

This repository contains the force field parameters, simulation input files, and initial structures for the molecular dynamics simulations of four camphor-based terpene mixtures (2:3 molar ratio) studied as CO₂ capture solvents.

| Abbreviation | Component    |
|--------------|--------------|
| CAM          | Camphor      |
| THY          | Thymol       |
| MEN          | Menthol      |
| CAR          | Carvone      |
| EUC          | Eucalyptol   |

## Contents

**`ff/`** — GROMACS-compatible force field files corresponding to the **modified Seminario (mSEM) parametrization** selected in the paper after benchmarking against experimental densities, and used for all simulations. Note that CO₂ uses the flexible EMP2 force field

**`ff_validation/`** — Force field files for the remaining parametrization strategies compared in the force field validation: standard GAFF2 (`ff_GAFF2/`), RESP charge reassignment (`ff_RESP/`), and fitted dihedrals (`ff_DH-fit/`).

**`mdp/`** — GROMACS run parameter files (.mdp) for energy minimization, equilibration, NPT production, NEMD viscosity, and HREX free energy simulations.

**`pdb/`** — PDB coordinate files for camphor, thymol, menthol, carvone, eucalyptol, and CO₂.

## Citation

If you use these files, please cite the accompanying publication.
