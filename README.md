# GFA ligand set

This repository contains the Galectin Fluorescence Anisotropy ligand set. This set comprises 1022 unique ligands with known $K_d$ values against Galectin-1 and -3 collected from literature and patents. All the $K_d$ values were measured by a single assay - fluorescence anisotropy (fluorescence polarization) assay. The set is categorized into several subsets based on structure and binding mode. Basic physicochemical properties are provided. The repository also contains docked poses in Galectin-3 (5H9P) and poses optimized with frozen protein at various levels of theory.

Paper: [![DOI](https://img.shields.io/badge/DOI-10.1021/acs.jcim.4c01659-green)](https://doi.org/10.1021/acs.jcim.4c01659)

Zenodo: [![DOI](https://zenodo.org/badge/853766036.svg)](https://doi.org/10.5281/zenodo.14585059)




# Composition of the ligand set

You can find the actual GFA ligand set in the file `GFA.csv`. The files `GFA_gal1.csv` and `GFA_gal3.csv` contain subsets of ligands with known affinities only to Gal-1 and Gal-3, respectively. The ligands are provided as SMILES strings and all necessary info (including the experimental $K_d$ value) for each ligand is also provided in these files. The composition of the set is as follows:



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

Distribution of the affinities towards Gal-1:

<img src="https://github.com/user-attachments/assets/769e5730-f661-48bc-9f06-1a5fb7626918" height="300">

Distribution of the affinities towards Gal-3:

<img src="https://github.com/user-attachments/assets/a80fe860-f8ae-4a25-8bac-70b146e857ba" height="300">


# Geometries

In the folder `geometries`, several rar files are provided with the ligand poses in the SDF format (V2000). First, geometries obtained by Glide SP docking into 5H9P structure of Gal-3 are provided. For some ligands, there is more than one ionization/tautomeric state. There are 10 docked poses for each ligand state. We also provide geometries that were obtained by optimizing the docked poses using three different methods (OPLS4/VSGB2.1, GFN-FF/ALPB, and GFN2/ALPB). These optimizations were all carried out with a frozen protein. The structures of the full protein and its truncated versions (12Å and 6Å globules) are provided as PDB files. The details of the docking procedure and the pose optimizations are provided in the above-mentioned paper.

# Energies

The folder `energies` contains binding enthalpies ($\Delta H_{bind}$) and binding free energies ($\Delta G_{bind}$) computed by several MM and SQM methods. These quantities are given for all the docked poses and also separately for the best pose per ligand. The individual energy terms are also provided. See the paper for details on how these values were calculated. The pictures below show examples of compounds GFA_4 (lactose) and GFA_8 (commercially known as GB0139) docked and scored in Galectin-3. The ligand poses (10 poses per ligand) are colored according to the relative $\Delta G_{bind}$ calculated by DFTB3-D4/COSMO. 

<img src="https://github.com/user-attachments/assets/0f4e76f7-6594-4a62-8891-55ebea55b2ee" height="400">
<img src="https://github.com/user-attachments/assets/72976dee-295e-415b-bdd9-a78f134bba05" height="400">



# License

The GFA ligand set is published under the MIT license. Do whatever you want with it.

