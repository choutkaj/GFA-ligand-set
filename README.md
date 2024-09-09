# GFA-ligand-set

This repository contains the Galectin Fluorescence Anisotropy ligand set. This set comprises 1022 unique ligands with known Kd values against Galectin-1 and -3 collected from literature and patents. All the Kd values were measured by a single assay - fluorescence anisotropy (fluorescence polarization) assay. The set is categorized into several subsets based on structure and binding mode. Basic physicochemical properties are provided. The repository also contains docked poses in Galectin-3 (5H9P) as well as poses optimized with frozen protein at various levels of theory.

<!-- The GFA ligand set was published in the following paper: -->


<!-- The GFA ligand set is also available at Zenodo: -->




# Composition of the ligand set


Series | No. of compounds | No. of Gal-1 affinities | No. of Gal-3 affinities 
--- | --- | --- | --- 
(Het)aryl-*C*-galactosides | 188 | 130 | 188
Alpha-thiogalactosides | 465 | 275 | 465
Beta-thiogalactosides | 59 | 24 | 59
LacNAc derivatives | 81 | 29 | 83
Lactose derivatives | 11 | 12 | 13
Monosaccharide derivatives | 108 | 87 | 97
Not a sugar | 1 | 1 | 1
Thiodisaccharide derivatives | 109 | 87 | 115
**Total** | **1022** | **645** | **1021**



# Affinities

Distribution of the affinities towards Gal-3:

<img src="https://github.com/user-attachments/assets/a80fe860-f8ae-4a25-8bac-70b146e857ba" height="300">

Distribution of the affinities towards Gal-1:

<img src="https://github.com/user-attachments/assets/769e5730-f661-48bc-9f06-1a5fb7626918" height="300">



# Geometries

In the folder "geometries", several rar files are provided which contain the ligand poses in the SDF format (V2000). First, geometries obtained by Glide SP docking into 5H9P structure of Gal-3 are provided. For some ligands, there is more than one ionization/tautomeric state. There are 10 docked poses for each ligand state. We also provide geometries that were obtained by optimizing the docked poses using three different methods. These optimizations were all carried out with a frozen protein. The structures of the full protein and its truncated version are provided as PDB files. The details of the docking procedure and the pose optimizations are provided in the above-mentioned paper

# Energies
The folder "energies" contains binding enthalpies computed by several MM and SQM methods. The binding enthalpies are given for all the docked poses, and also for the best pose per ligand. See the above-mentioned paper for the details of these calculations.

