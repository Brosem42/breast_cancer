# breast_cancer
# Predicting Malignancy in Breast Cancer Using Logistic Regression
This project uses logistic regression to predict whether a breast cancer is malignant or benign based on the features of 'worst concavity' and 'worst area'. The logistic regression model is trained and evaluated on the `load_breast_cancer` dataset from scikit-learn.

## Attributes
The following attributes are included in the `load_breast_cancer` dataset:

- `mean radius`: mean of the distances from center to points on the perimeter.
- `mean texture`: standard deviation of gray-scale values.
- `mean perimeter`: mean size of the core tumor.
- `mean area`: mean area of the core tumor.
- `mean smoothness`: mean of local variation in radius lengths.
- `mean compactness`: mean of perimeter^2 / area - 1.0.
- `mean concavity`: mean of severity of concave portions of the contour.
- `mean concave points`: mean for number of concave portions of the contour.
- `mean symmetry`: mean symmetry of the tumor.
- `mean fractal dimension`: mean for "coastline approximation" - 1.
- `radius error`: standard error for the mean of distances from center to points on the perimeter.
- `texture error`: standard error for standard deviation of gray-scale values.
- `perimeter error`: standard error for mean size of the core tumor.
- `area error`: standard error for the mean area of the core tumor.
- `smoothness error`: standard error for mean of local variation in radius lengths.
- `compactness error`: standard error for mean of perimeter^2 / area - 1.0.
- `concavity error`: standard error for mean of severity of concave portions of the contour.
- `concave points error`: standard error for mean for number of concave portions of the contour.
- `symmetry error`: standard error for mean symmetry of the tumor.
- `fractal dimension error`: standard error for mean for "coastline approximation" - 1.
- `worst radius`: "worst" or largest mean value for mean of distances from center to points on the perimeter.
- `worst texture`: "worst" or largest mean value for standard deviation of gray-scale values.
- `worst perimeter`: "worst" or largest mean value for mean size of the core tumor.
- `worst area`: "worst" or largest mean value for the mean area of the core tumor.
- `worst smoothness`: "worst" or largest mean value for mean of local variation in radius lengths.
- `worst compactness`: "worst" or largest mean value for mean of perimeter^2 / area - 1.0.
- `worst concavity`: "worst" or largest mean value for mean of severity of concave portions of the contour.
- `worst concave points`: "worst" or largest mean value for mean for number of concave portions of the contour.
- `worst symmetry`: "worst" or largest mean value for mean symmetry of the tumor.
- `worst fractal dimension`: "worst" or largest mean value for mean for "coastline approximation" - 1.

## Model Evaluation
The logistic regression model was evaluated using 4-folds with the following cross-validated accuracy scores: `[0.93006993 0.93661972 0.95070423 0.93661972]` and the mean cross-validated accuracy was `0.9385`. The model's intercept was `0.33808955` and the relationship between the features 'worst concavity' and 'worst area' to the target result were `-1.48290324` and `-4.28202054` respectively. The accuracy of the model was `0.9532` and the F1-score was `0.9636`.

## Dataset
The dataset used in this project, `load_breast_cancer`, can be found on the scikit-learn website: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

## Installation
The project was developed using Anaconda distribution, which can be installed using the following command in the command-line interface (CLI):

conda install anaconda

Alternatively, the distribution can be downloaded from the following link: https://www.anaconda.com/products/distribution

## Libraries Imported
The following libraries were imported for this project:
- `scikit-learn`
- `pandas`
- `numpy`
- `matplotlib`

## Performance Summary
The performance of the logistic regression model was evaluated using various metrics, such as accuracy and F1-score. The results show that the model has a high accuracy in classifying the breast cancer as either malignant or benign.

## Possible Improvements
Ways to improve the performance of the logistic regression model in future cases:
- Using additional features from the dataset
- Hyperparameter tuning to find the optimal values for the logistic regression model
- Using different evaluation metrics to measure the performance of the model
- Using a different machine learning algorithm to classify the breast cancer.


