# Computation of Abstract Sameness Relations in PLMs

This repo contains our code for paper LINK.

The original experiment can be performed by running experiments.ipynb. For the seen data experimental setting a pmi index for the respective model is mandatory and can be created using pmi_index.ipynb.

All code was developed on the Google Research platform Colaborytory (Google Colab). In order to run the experiments (experiments.ipynb), GPU processing (CUDA) is required. Due to the high demand of resources related to the pmi index creation (pmi_index.ipynb), a Cloud TPU machine was used. 
Moreover, a google drive integration was implemented for an easier file management. Thus, if the code is not executed on Google Colab, several adaptations will be necessary.
