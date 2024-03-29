# Introduction
This project will focus on trying to simulate the decision-making of a human researcher using a Bayesian Optimization framework, then comparing the performance across different, improved hyperparameters. By exploring these differences, this project aims to understand the strengths and weaknesses of Bayesian Optimization relative to the decision-making of a researcher with access to the same data.

We will look at three hyperparameters that can be used to define the differences between a researcher and regular Bayesian Optimization: the number of features that can be processed, the degree of exploration vs exploitation, and the interpretability/complexity of the surrogate model.

# Usage
Please go to the `src` folder and run `BOv4.ipynb` to run the Bayesian Optimization over one set of hyperparameters. Once all hyperparameters have been run, please use `01-eda.ipynb` to plot the results.
