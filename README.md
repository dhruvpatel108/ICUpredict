# ICUpredict
Official implementation of [Machine Learning Based Predictors for COVID-19 Disease Severity](https://www.researchsquare.com/article/rs-108301/v1) work. Here we provide the data and the code for our model.

## Objective
The goal of this work is to predict the the need of intensive care and mechanical ventilation for COVID-19 patients from socio-demographic, clinical, and blood-profile data available at the time of initial admission. De-identified patient data was colleced from 3 different hopitals in Los Angeles county in an IRB-approved study and 6 different machine learning algorithms were trained using this data.

## Requirements
* Python 3.7
* [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
* [Numpy](https://numpy.org/)
* [scikit-learn](https://scikit-learn.org/stable/install.html)
* [Scipy](https://www.scipy.org/install.html)
* [seaborn](https://seaborn.pydata.org/installing.html)
* [Matplotlib](https://matplotlib.org/users/installing.html)


## Usage
De-identified patient data is provided in a pickle file (`./data/raw_features_DDupdated_212.pkl`) and the code for data processing, modeling and post-processing is provided as a jupyter notebook (`model_icu.ipnyb`).

## Cite the paper
If you find this useful or use data/code from this repo, then please cite the following paper:
```
@article{Patel2021Machine,
abstract = {Predictors of the need for intensive care and mechanical ventilation can help healthcare systems in planning for surge capacity for COVID-19. We used socio-demographic data, clinical data, and blood panel profile data at the time of initial presentation to develop machine learning algorithms for predicting the need for intensive care and mechanical ventilation. Among the algorithms considered, the Random Forest classifier performed the best with AUC = 0.80 for predicting ICU need and AUC = 0.82 for predicting the need for mechanical ventilation. We also determined the most influential features in making this prediction, and concluded that all three categories of data are important. We determined the relative importance of blood panel profile data and noted that the AUC dropped by 0.12 units when this data was not included, thus indicating that it provided valuable information in predicting disease severity. Finally, we generated RF predictors with a reduced set of five features that retained the performance of the predictors trained on all features. These predictors, which rely only on quantitative data, are less prone to errors and subjectivity.},
author = {Patel, Dhruv and Kher, Vikram and Desai, Bhushan and Lei, Xiaomeng and Cen, Steven and Nanda, Neha and Gholamrezanezhad, Ali and Duddalwar, Vinay and Varghese, Bino and Oberai, Assad A.},
doi = {10.1038/s41598-021-83967-7},
file = {:C$\backslash$:/Users/Harikrishna/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Patel et al. - 2021 - Machine learning based predictors for COVID-19 disease severity.pdf:pdf},
issn = {20452322},
journal = {Scientific Reports},
keywords = {Machine learning,Outcomes research,Prognosis},
month = {dec},
number = {1},
pages = {4673},
pmid = {33633145},
publisher = {Nature Research},
title = {{Machine learning based predictors for COVID-19 disease severity}},
url = {https://doi.org/10.1038/s41598-021-83967-7},
volume = {11},
year = {2021}
}


