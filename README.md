# Wine Judge

Wine Judge is a small machine learning project that predicts the quality of red and white wines using various classification algorithms. The project demonstrates data preprocessing, feature scaling, model training, evaluation, and comparison of multiple classifiers on the UCI Wine Quality datasets.

## Project Overview

This project explores the physicochemical properties of red and white wines to classify their quality into three categories: Low, Mid, and High. The workflow includes:

- Data loading and cleaning
- Feature engineering and scaling
- Splitting data into training and testing sets
- Training and evaluating multiple ML models:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Stochastic Gradient Descent (SGD)
- Comparing model performance using accuracy and cross-validation metrics
- Visualizing results

## Files

- [`red_wine_judge.ipynb`](red_wine_judge.ipynb): Jupyter notebook for red wine quality classification.
- [`white_wine_judge.ipynb`](white_wine_judge.ipynb): Jupyter notebook for white wine quality classification.

## Dataset

The project uses the [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality) by P. Cortez et al. The datasets (`winequality-red.csv` and `winequality-white.csv`) contain physicochemical test results and quality ratings for red and white wines.

## How to Run

1. Download the datasets and place them in the same directory as the notebooks.
2. Open either notebook in Jupyter or Google Colab.
3. Run all cells to preprocess data, train models, and view results.

## Results

The notebooks output classification reports and plots comparing the performance of each model. Metrics include test accuracy, cross-validation mean accuracy, and standard deviation.

## References

- P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. "Modeling wine preferences by data mining from physicochemical properties." Decision Support Systems, Elsevier, 47(4):547-553, 2009. [DOI](http://dx.doi.org/10.1016/j.dss.2009.05.016)

---

*This project is for educational purposes and demonstrates basic machine learning workflows on real-world data.*
