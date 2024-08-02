# Discrete-Molecular-Dynamics-Data-Analysis-Utilities
## Introduction
This GitHub repository contains utility programs for the analysis of simulation data generated by Discrete Molecular Dynamics (DMD, available at [Molecules in Action, LLC](https://www.moleculesinaction.com/pdmd.html)).
DMD is a molecular dynamics algorithms with significantly improved computational efficiency and proven accuracy in wide applications. 
The utility programs in this repository are designed to analyze large simulation datasets generated in DMD simulations. 

## Dependencies
* Python, version 3.7 or later is recommended. The needed libraries:
  * Matplotlib (https://matplotlib.org)
  * Numpy (https://numpy.org)
* Awk (https://github.com/onetrueawk/awk)

## Secondary structure contents
*ssCont.awk* can rapidly calculate the contents of the secondary structures of the entire protein system for each DMD trajectory frame.
This script takes the standard DSSP output from DMD as the input file.
Usage:
```bash
awk ssCont.awk in_dssp.example > out_ssCont
```
The columns from left to right contains the contents of the four secondary structure types, respectively:
* Helix, β-sheet, Turn, Random coil

If you need more detailed information of a specific peptide chain, *ssmap-fr.py* will calculate the secondary structure propensity on each residue.

*(In construction)*

<?
## Fibrillar aggregate morphology analysis
Briefly, we can differentiated protein aggregates using their respective morphologies, i.e. number of layers and β-sheet sizes. The two types of fibrillar aggregates are: 
* Amyloid fibrils, which has a small number of β-sheet layers (typicall 2). Example
* Nanocrystals, which has a large number of layers (typically 2+ ). Example
In a given molecular system, the total number of peptide chains is constant. Therefore, a nanocrystal conformation will have more layers but small-sized β-sheets, while a fibril will have fewer layers but large-sized β-sheets.


## 2-dimensional PMF visualization
?>
