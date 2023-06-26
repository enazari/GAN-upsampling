# Leveraging CGAN for Addressing Class Imbalance, Small Sample Size, and Data Difficulty Factors in Cybersecurity and Imagery Datasets

This repository contains all the code used in the experiments carried out in the papers *Using CGAN to Deal with Class Imbalance and Small Sample Size in Cybersecurity Problems* [1] and *On Oversampling via Generative Adversarial Networks under Different Data Difficult Factors* [2].

dataset-builder.ipynb, utils.ipynb, and tester.ipynb are the necessary files to redo all the tests conducted in the paper. 

In order to reproduce the results in Google Colab one needs to:
* copy these files to a directory in Google Drive and change the directory address in the dataset-builder.ipynb and tester.ipynb files according the current directory
* execute the code inside the dataset-bulider file
* create a folder named datasets and cut the created datasets into it
* create a new empty csv file names results.csv
* open tester.ipynb file and execute the code; all the results will be recorded into results.csv file

*****

### References
[1] Nazari, Ehsan, Paula Branco, and Guy-Vincent Jourdan. "Using cgan to deal with class imbalance and small sample size in cybersecurity problems." 2021 18th International Conference on Privacy, Security and Trust (PST). IEEE, 2021.
[2] Nazari, Ehsan, and Paula Branco. "On oversampling via generative adversarial networks under different data difficulty factors." Third international workshop on learning with imbalanced domains: Theory and applications. PMLR, 2021.
