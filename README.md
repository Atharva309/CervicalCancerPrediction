# Predicting Cervical Cancer

This project aims to predict the likelihood of cervical cancer using data on various risk factors associated with the disease. The dataset used in this project was obtained from the UCI Machine Learning Repository, and contains information on 858 patients who were tested for cervical cancer.

# Dataset

The cervical cancer dataset contains 36 columns, including 1 target variable ('Biopsy') and 35 predictor variables related to various risk factors for cervical cancer, such as age at first sexual intercourse, number of sexual partners, and use of contraceptives. The dataset also includes missing values, which were imputed using the mean value of each column.
The cervical cancer dataset used in this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Cervical+cancer+%28Risk+Factors%29)
, and was originally collected by Kelwin Fernandes de Mesquita, Guilherme de Alencar Barreto, and Paulo P. Rebouças Filho.

# Project Details

The project involves training a logistic regression model to predict the likelihood of cervical cancer based on the predictor variables in the dataset. The model was trained on a randomly selected 80% of the dataset, and evaluated on the remaining 20%. The accuracy of the model was measured using the score function from scikit-learn.
The following Python libraries are required to run the project:pandas, numpy, scikit-learn.
