# ICUpredict
Official implementation of Machine Learning Based Predictors for COVID-19 Disease Severity work. Here we provide the data and the code for our model.

## Objective
The goal of this work is to predict the the need of intensive care and mechanical ventilation for COVID-19 patients from socio-demographic, clinical, and blood-profile data available at the time of initial admission of patients. De-identified patient data was colleced from 3 different hopitals in Los Angeles county in an IRB-approved study and 6 different machine learning algorithms were trained using this data.

## Requirements
* Python 3.7
* [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
* [Numpy](https://numpy.org/)
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* [Scipy](https://www.scipy.org/install.html)
* [seaborn](https://seaborn.pydata.org/installing.html)
* [Matplotlib](https://matplotlib.org/users/installing.html)


## Usage
De-identified patient data is provided in a pickle file (`./data/`) and the code for data processing, modeling and post-processing is provided as a jupyter notebook (`model_icu.ipnyb`).
