# Data folder
This folder contains the code to preprocess the PR2 dataset and to generate the train-test data splits for the experiments.

Folder:
- **PR2**: A placeholder folder where the original PR2 data¹ must be added to run the scripts  

Files:
- **data_cleaning.ipynb**: Notebook script to clean the original PR2 dataset from ``./PR2`` folder, keeping only the relevant data and generating new features. Saves the preprocessed dataset as ``cleaned_sequences.csv`` in the ``./PR2`` folder
- **data_generator.ipynb**: Notebook script to generate the train-test data, saving them in the ``../new_data`` folder

> ¹Note: A copy of PR2 folder with preloaded data can be downloaded from [the project assets >here<](https://github.com/GSFrainer/DeepLearning_Taxonomy_Classification/releases/tag/rs-data-v1.0). The original PR2 dataset used in this work, ``pr2_version_5.0.0_merged.xlsx``
,  can be accessed at [>this link<](https://github.com/pr2database/pr2database/releases/tag/v5.0.0).
