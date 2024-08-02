# Discrete-Molecular-Dynamics-Data-Analysis-Utilities
## Introduction
This GitHub repository contains utility programs for the analysis of simulation data generated by Discrete Molecular Dynamics (DMD, available at [Molecules in Action](https://www.moleculesinaction.com/pdmd.html)).
DMD is a molecular dynamics algorithms with significantly improved computational efficiency and proven accuracy in wide applications. 
The utility programs in this repository are designed to analyze large simulation datasets generated in DMD simulations. 

## Dependencies
* Python, version 3.7 or later is recommended. The needed libraries:
  * Matplotlib (https://matplotlib.org)
  * Numpy (https://numpy.org)
* Awk (https://github.com/onetrueawk/awk)

<?
## Secondary structure contents

## Fibrillar aggregate morphology analysis
This program is used for deciding the type of fibrillar aggregate formed by protein or peptide chains. 
Briefly, we can differentiated protein aggregates using their respective number of layers and β-sheet sizes. The two types of fibrillar aggregates are: 
* Amyloid fibrils, which has a small number of β-sheet layers (typicall 2)
* Nanocrystals, which has a large number of layers (typically 2+ )
In a given molecular system, the more layers will lead to a decrease in the β-sheet size. Therefore, a nanocrystal conformation will have more layers but small-sized β-sheets, while a fibril will have fewer layers but large-sized β-sheets.

## 2-dimensional PMF visualization
?>
