# Machine Learning Lab

Practical work from my Machine Learning lab course. Each notebook implements one core
technique in Python, from data preprocessing through regression, classification,
clustering, association rules and a basic neural network.

**Tech:** Python · NumPy · pandas · scikit-learn · TensorFlow / Keras · Matplotlib · seaborn · mlxtend

## Contents

| # | Notebook | Topic | What it covers |
|---|----------|-------|----------------|
| 1 | [First_ML.ipynb](First_ML.ipynb) | Linear regression | First end-to-end model: train/test split, fit and error metrics |
| 2 | [Second_ML.ipynb](Second_ML.ipynb) | Exploratory data analysis | Iris dataset summaries, histograms and pair plots |
| 3 | [Data_Preprocessing_ML_3rd .ipynb](Data_Preprocessing_ML_3rd%20.ipynb) | Data preprocessing | Boston Housing data: cleaning, label encoding and feature scaling |
| 4 | [ML_Lab_4th.ipynb](ML_Lab_4th.ipynb) | PCA from scratch | Standardisation, covariance matrix and eigen-decomposition with NumPy |
| 5 | [ML_Lab_5th.ipynb](ML_Lab_5th.ipynb) | K-Nearest Neighbours | KNN classifier with a confusion matrix |
| 6 | [lab6.ipynb](lab6.ipynb) | Decision tree | Pima Indians Diabetes classification and tree visualisation |
| 7 | [NBLab7.ipynb](NBLab7.ipynb) | Naive Bayes | Categorical Naive Bayes on encoded features |
| 8 | [Practical_8_of_ML.html](Practical_8_of_ML.html) | Random forest | Exported notebook of a random forest classifier |
| 9 | [ML Lab 9.ipynb](ML%20Lab%209.ipynb) | Simple linear regression | Study hours vs test score, with MAE, MSE and RMSE |
| 10 | [ML lab 10th.ipynb](ML%20lab%2010th.ipynb) | Multiple linear regression | Two predictors, coefficients, residuals and R² |
| 11 | [Practical 11.ipynb](Practical%2011.ipynb) | Logistic regression | Binary classification with scikit-learn |
| 12 | [Practical12.ipynb](Practical12.ipynb) | Logistic regression from scratch | Sigmoid, log-loss and gradient descent in NumPy |
| 13 | [KMean.ipynb](KMean.ipynb) | K-Means clustering | Customer segmentation on income and spending score |
| 13b | [KNN 2.ipynb](KNN%202.ipynb) | K-Means clustering | Elbow method to choose the number of clusters |
| 14 | [practical14.ipynb](practical14.ipynb) | Association rules | Apriori frequent itemsets and rules on market-basket data |
| 15 | [ML_15_ANN.ipynb](ML_15_ANN.ipynb) | Artificial neural network | Keras multi-class classifier on the Iris dataset |

## Running the notebooks

Every notebook runs in [Google Colab](https://colab.research.google.com/) or locally with Jupyter:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn mlxtend tensorflow jupyter
jupyter notebook
```

Most notebooks use built-in or inline datasets. `First_ML.ipynb` and `KNN 2.ipynb` read a
local CSV file that needs to be uploaded alongside them.
