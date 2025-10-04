# Diamonds Regression and Classification
This repository contains two projects on the Diamonds dataset

1. **Linear Regression** - predicting the diamond prices
2. **Logistic Regression** - classifying the prices into 4 bins

Both notebooks explore and test preproccesing, feature engineering, model training, and evaluation.

## Notebooks Overview

1. **Linear Regression**
   - Predics diamond prices
   - Techniques: Ordinal Encoding, Log-Scaling, Feature Engineering, TrainTestSplit, and evaluation using Scatter Plots
   - Key Takeaway: log-scaling drastically improved the score: ~0.90 to ~0.97
   - Some thoughts: I had an amazing time coding this model, espacially at the time of finding out the huge difference log-scaling made while testing out scaling methods

2. **Logistic Regression**
   - Categorizes the prices into 4 bins
   - Techniques: Ordinal Encoding,  Feature Engineering, Standard Scaling, GridSearchCV + Pipeline, and Confusion Matric for evaluation
   - Key Takeaway: Even small differences in predicted price can rezult in misclasification, overall score: ~0.92
   - Some thoughts: It is the first classifier that I ran on a regression dataset (converted into a classification dataset). Personally, the most important part of this notebook was the **Confusion Matrix**, showing that a score of ~0.92 can be somewhat decieving, as in reality the predictions are often very close but considered wrong because they where classified int to a bin adjecent to the correct one because of a small value difference
  
## Requirements
  - Python: 3.13.7
  - Libraries: pandas, numpy, seaborn, scikit-learn, matplotlib
  Install requirements by:
  ```bash
  git clone https://github.com/alexlakabus/Linear-Logistic-Regression.git
  ```
  Open the notebooks in VS Code or Jupyter Notebook

## Key Notes
  - Both notebooks contain documented information about each model and their behavior on the dataset
  - Both show the importance of understanding core model principles and data preprocessing, while showing the thought procces behind certain decisions

