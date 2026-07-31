---
title: "DES-AMBER for GROMACS"

summary: "A GROMACS-compatible conversion of the DES-AMBER RNA force field for use in GROMACS molecular dynamics workflows."

date: "2026-07-31T00:00:00Z"

authors:
  - admin

tags:
  - "Software"
  - "RNA"
  - "Force Field"
  - "Molecular Dynamics"
  - "GROMACS"

featured: false

# Keep this empty so that the Resources card opens this internal detail page.
external_link: ""
---

## Overview

This resource provides a GROMACS-compatible conversion of the DES-AMBER RNA force field introduced by Tan and co-workers. The original force-field parameters have been organized into a GROMACS `.ff` directory so that DES-AMBER can be selected and used through standard GROMACS workflows.

The converted files are intended to make the original DES-AMBER parameters more accessible to researchers performing RNA molecular dynamics simulations with GROMACS. This GROMACS-compatible version was also used in the simulations associated with our HB-CUFIX study.

## Force-Field Files

- [Download DES-AMBER for GROMACS](https://cobailab.github.io/downloads/Des_AMBER.ff.zip)
- [Browse the GROMACS-compatible files on GitLab](https://gitlab.com/KirmizialtinLab/des_amber/)

## Installation

Copy the GROMACS-compatible force-field folder into your working directory:

```bash
cp -r Des_AMBER.ff /path/to/your/working/directory/
```

## Usage

Prepare the RNA system using `gmx pdb2gmx`:

```bash
gmx pdb2gmx -f RNA_structure.pdb
```

When prompted to select a force field, choose the DES-AMBER entry from the current working directory:

```text
DES_AMBER: GROMACS-compatible version of the DES-AMBER RNA force field
```

## Compatibility and Validation

The converted files provide a practical implementation of DES-AMBER for GROMACS and have been used in our RNA simulation workflow. Because force-field conversion can involve differences in topology conventions, parameter mapping, and software versions, users are encouraged to inspect the generated topology and validate representative systems before beginning production simulations.

Please report any conversion-related issues or inconsistencies so that the resource can be further evaluated and improved.

## Original Reference

Dazhi Tan, Stefano Piana, Robert M. Dirks, and David E. Shaw.

**“RNA Force Field with Accuracy Comparable to State-of-the-Art Protein Force Fields.”**

*Proceedings of the National Academy of Sciences* **2018**, **115**(7), E1346–E1355.

[View Publication](https://doi.org/10.1073/pnas.1713027115)
