Forecasting Startup's Acquisition from Crunchbase data
=============

Instructions
-------

* Raw initial data files are: `data/acquisitions.csv`, `data/companies.csv`, `data/investments.csv` and `data/rounds.csv`
* Folder `exploratory_code` contains old and messy code used during exploratory analysis
* Files `dataset_preparation.ipynb` and `modelling.ipynb` contains all the code (with comments) necessary to prepare the dataset and run the analysis. First, run `dataset_preparation.ipynb`, which will output the prepared dataset in `data/startups_pre_processed.csv`, then run `modelling.ipynb`.



Dependencies
-------
Python 2.7
Scikit-Learn and its dependencies (numpy, pandas, etc..)
https://github.com/scikit-learn-contrib/imbalanced-learn
https://github.com/dmlc/xgboost (optional)