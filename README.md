# ISL-python

[*An Introduction to Statistical Learning*](http://www-bcf.usc.edu/~gareth/ISL/) is a textbook by Gareth James, Daniela Witten, Trevor Hastie and Robert Tibshirani. Conceptual and applied excercises are provided at the end of each chapter covering supervised learning.


<IMG src='http://www-bcf.usc.edu/%7Egareth/ISL/ISL%20Cover%202.jpg' height=20% width=20%> <P>
  
This repository contains my solutions to the labs and excercises as Jupyter Notebooks written in Python using:

- Numpy
- Pandas
- Matplotlib
- Seaborn
- Patsy
- StatsModels
- Sklearn


Perhaps of most interest will be the recreation of some functions from the R languge that I couldn't find in the Python ecosystem. These took me some time to reproduce but the implementation details are not essential to the concepts taught in the book so please feel free to reuse. For example, a reproduction of R's `lm()` four-way diagnostic plot for linear regression in Chapter 3. Also, a collection of [all required datasets]((./Notebooks/data)) is provided in .csv format.


## To view notebooks

Links to view each notebook below. The code is provided [here](./Notebooks).  

[Chapter 2 - Statistical Learning: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch2_statistical_learning_conceptual.ipynb)  
[Chapter 2 - Statistical Learning: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch2_statistical_learning_applied.ipynb)


[Chapter 3 - Linear Regression: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch3_linear_regression_conceptual.ipynb)  
[Chapter 3 - Linear Regression: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch3_linear_regression_applied.ipynb)


[Chapter 4 - Classification: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch4_classification_conceptual.ipynb)  
[Chapter 4 - Classification: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch4_classification_applied.ipynb)


[Chapter 5 - Resampling Methods: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch5_resampling_methods_conceptual.ipynb)  
[Chapter 5 - Resampling Methods: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch5_resampling_methods_applied.ipynb)


[Chapter 6 - Linear Model Selection and Regularization: Labs](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch6_linear_model_selection_and_regularisation_labs.ipynb)  
[Chapter 6 - Linear Model Selection and Regularization: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch6_linear_model_selection_and_regularisation_conceptual.ipynb)  
[Chapter 6 - Linear Model Selection and Regularization: Applied](https://github.com/a-martyn/ISL-python/blob/master/Notebooks/ch6_linear_model_selection_and_regularisation_applied.ipynb)


[Chapter 7 - Moving Beyond Linearity: Labs](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch7_moving_beyond_linearity_labs.ipynb)  
[Chapter 7 - Moving Beyond Linearity: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch7_moving_beyond_linearity_applied.ipynb)


[Chapter 8 - Tree-Based Methods: Labs](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch8_tree_based_methods_labs.ipynb)  
[Chapter 8 - Tree-Based Methods: Conceptual](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch8_tree_based_methods_conceptual.ipynb)  
[Chapter 8 - Tree-Based Methods: Applied](http://nbviewer.jupyter.org/github/a-martyn/ISL-python/blob/master/Notebooks/ch8_tree_based_methods_applied.ipynb)


## To run notebooks

Running thes notebooks enables you to execute the code and play around with any interactive features.

To run these notebooks:

1. [Install Jupyter Notebooks](https://jupyter.readthedocs.io/en/latest/install.html). I reccomend doing this via annaconda and conda method which ensure that python package versions play nicely together.
2. `cd` to this repo
3. Run `jupyter notebook` to run the jupyter server locally on your machine. It should launch in your browser.
4. In the Jupyter browser app, navigate to the notebook you'd like to explore.
