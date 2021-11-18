# Data Science
This repository stores some data science projects. These projects are mainly written in python and organized as jupyter notebooks (notebooks for short). 

## Environments
I run these notebooks in anaconda environments. Each notebook basically uses its own conda environment where the installed python packages are different from others. The required packages are listed at the end of each notebook, except for notebooks which use only basic data science packages such as numpy, scipy, pandas, and matplolib. 

## Repository organization
There are four main directories in this repository. New directories may be added in the future.
- `datasets` is where raw datasets are stored. It is likely to be empty here on github. One needs to download the required datasets stated in a notebook if he or she whats to run that notebook.
- `repository` is where any temporary objects, such as preprocessed data or trained model, are kept for later usage. It is likely to be empty here on github. The name `repository` has nothing to do with "git repository".
- `data_cleaning` stores notebooks which perform data cleaning. These notebooks often read raw data from `datasets` and save the cleansed data in `repository`.
- `data_analysis` stores notebooks which perform data analysis. These notebooks often read cleansed data from `repository`, and may save some objects to `repository`.

## Choose a data science project to run
To run a project, launch one of the notebooks listed below and perform the required actions stated in that notebook, including launching some other notebooks and/or downloading some datasets.
Here list the available projects. More may be added in the future.

## To do list
- pipreqsnb prints `scikit_learn` rather than `scikit-learn`. Is this correct?
- Merge some frequently used code into a utility code file.
