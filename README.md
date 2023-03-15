# Predicting Malignancy in Breast Cancer Using Logistic Regression
This project uses logistic regression to predict whether a breast cancer is malignant or benign based on the features of 'worst concavity' and 'worst area'. The logistic regression model is trained and evaluated on the `load_breast_cancer` dataset from scikit-learn.

## Data Set Characteristics

The dataset used in this project, `load_breast_cancer`, can be found on the scikit-learn website: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

The `load_breast_cancer` dataset used for this project contains 569 instances & 30 numeric, predictive attributes. The dataset includes the following attributes:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension (“coastline approximation” - 1)

The mean, standard error, and “worst” or largest (mean of the three worst/largest values) of these features were computed for each image, resulting in 30 features. The class of the target variable is either `WDBC-Malignant` or `WDBC-Benign` with 212 instances of `Malignant` and 357 instances of `Benign`. The data was created by Dr. William H. Wolberg, W. Nick Street, and Olvi L. Mangasarian and donated by Nick Street in November, 1995. There are NO missing attributes in the dataset.

## Model Evaluation
The logistic regression model was evaluated using 4-folds with the following cross-validated accuracy scores: `[0.93006993 0.93661972 0.95070423 0.93661972]` and the mean cross-validated accuracy was `0.9385`. The model's intercept was `0.33808955` and the relationship between the features 'worst concavity' and 'worst area' to the target result were `-1.48290324` and `-4.28202054` respectively. The accuracy of the model was `0.9532` and the F1-score was `0.9636`.

## Installation
The project was developed using Anaconda distribution, which can be installed using the following command in the command-line interface (CLI):

conda install anaconda

Alternatively, further instructions on installation can be accessed through the following link: https://www.anaconda.com/products/distribution

## Libraries Imported
The following libraries were imported for this project:
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

## Performance Summary
The performance of the logistic regression model was evaluated using various metrics, such as accuracy and F1-score. The results show that the model has a high accuracy in classifying the breast cancer as either malignant or benign.

## Possible Improvements
Ways to improve the performance of the model in future cases:
- Using additional features from the dataset
- Hyperparameter tuning to find the optimal values for the logistic regression model
- Using different evaluation metrics to measure the performance of the model
- Using a different machine learning algorithm to classify the breast cancer.
