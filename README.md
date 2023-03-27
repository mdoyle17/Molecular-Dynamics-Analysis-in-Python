## Molecular Dynamics Analysis in Python

Enclosed are scripts used for analyzing MD simulations of PS II in python.
Below is a brief description:

## files_for_plots 
Contains relevant .pdb, .dat, .pkl etc. files used in this work. These are all necesary for the .ipynb files under the scripts directory

## scripts
Several .ipynb files are enclosed which exhibit a range of functionalities, currently including the following:  
- Script for checking temperature and pressure of a simulation 
- Script for comparing geometry of active site in simulation to reference structure
- Script for generating .gro and .top files 
- Script for map-based Hydrogen bonding analysis 
- Script for computing recall of crystallographic waters in water channels as well as around the active site 
- Script for computing distance of randomly selected bulk waters to active site 


## itp
Topology folder for this work

## strong_peaks_in_20_angstrom_of_OEC.pdb
.pdb file contaning coordinates of additional waters from the simulation which are likely to be in the PS II S1 structure (within 20 Angstrom of OEC)

## 0F.pdb_fittedto55all.pdb
reference PS II structure used for this work - can be loaded up in Coot and overlaid with strong_peaks_in_20_angstrom_of_OEC.pdb for comparison
