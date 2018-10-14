# Parallel Computing Assignment

The R Markdown notebook main.Rmd imports a list of molecules in the `.sdf` format. The data I used can be downloaded from PubChem (PubChem Assay AID 624202). A pre-set number of molecules are imported and then the molecular descriptors are computed in parallel. This is done multiple times for various amounts of cores to use for the calculation. To allow for parallel computing, the molecules are first converted into smiles and then parsed back into the molecules by each core. The code can be adapted to run in parallel over the descriptors instead of over the molecules.

A compiled notebook is hosted here. The files necessary to reproduce the compiled notebook can be found at github, as well as PubChem. The notebook automatically takes care of installing and loading all required packages. Thus, you only need to change the file directory to let the notebook import the necessary files.
