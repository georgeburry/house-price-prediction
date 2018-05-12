# Predicting Boston house prices

This is a simple example of how to: take a modest dataset, distill the feature set through exploratory data analysis, and then scale the features and train a variety of regression models via a pipeline. In the end, I select the random forest regression model, which typically yields very good results, and apply a grid search to tune model parameters, before predicting prices.

Scikit-learn includes a default dataset to work with called Boston House Prices. This data is obtained by making a call to the Scikit-learn API, so there is no need to fetch the data externally.

## Installation

1. Clone or download this repository to your computer.
2. Install Jupyter Lab (**pip install jupyterlab**).
3. cd to the directory of the repository.
4. Launch Jupyter Lab using the following command: **jupyter lab**.
5. The notebook can be opened and run inside Jupyter Lab window.
