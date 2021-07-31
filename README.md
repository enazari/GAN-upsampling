# On Oversampling via GANs under Different Data Difficult Factors - LIDTA 2021

This repository contains all the code used in the experiments carried out in the paper *""On Oversampling via Generative Adversarial Networks under Different Data Difficult Factors " International Workshop on Learning with Imbalanced Domains: Theory and Applications. PMLR, 2021"* [1].

dataset-builder.ipynb, utils.ipynb, and tester.ipynb are the necessary files to redo all the tests conducted in the paper. 

In order to reproduce the results in Google Colab one needs to:
* copy these files to a directory in Google Drive and change the directory address in the dataset-builder.ipynb and tester.ipynb files according the current directory
* execute the code inside the dataset-bulider file
* create a folder named datasets and cut the created datasets into it
* create a new empty csv file names results.csv
* open tester.ipynb file and execute the code; all the results will be recorded into results.csv file

*****

### References
[1] Nazari, Ehsan and  Branco, Paula "On Oversampling via Generative Adversarial Networks under Different Data Difficult Factors " International Workshop on Learning with Imbalanced Domains: Theory and Applications. PMLR, 2021.
