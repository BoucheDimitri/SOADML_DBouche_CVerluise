# Stochastic Optimization and Automatic Differentiation for Machine Learning
### Comparisons of SDCA and Pegasos applied to bloodcells images classification

Authors : Dimitri Bouche & Cyril Verluise

## Getting started

There are two main notebooks : 
* *Images_Processing.ipynb* : it implements pre-processing steps on the images from the database. It requires the library opencv2 to run.
* *SDCA_vs_Pegasos.ipynb* : the main notebook running the comparison on the dataset processed by Images_Processing.ipynb. It requires no very specific library to run (apart from standards python scientific libraries)

**Important** : the version of the database transformed by Images_Processing.ipynb is available in
the repository (https://github.com/BoucheDimitri/SOADML_DBouche_CVerluise.git), it is the **/Cropped** folder. So one can run only the notebook SDCA_vs_Pegasos.ipynb
by downloading this folder from the repository and putting it in the same folder as the notebooks.

*Remark : the raw database is also available in the repository (https://github.com/BoucheDimitri/SOADML_DBouche_CVerluise.git), it is the **/Bloodcells** folder, if one wants to run the Images_Processing notebook, one must download this folder as well and put it in the same folder as the notebooks*





