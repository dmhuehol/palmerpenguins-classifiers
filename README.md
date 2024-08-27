# palmerpenguins-classifiers

This repository contains Google Colab notebooks to demonstrate applying different machine learning methods for classification tasks. They use the Palmer Penguins dataset ([Horst et al. 2022](http://doi.org/10.32614/RJ-2022-020)), which consists 
of measurements of penguins from islands in the Palmer Archipelago in Antarctica between 2007 and 2009. Algorithms trained on these measurements can predict the species of penguin for a given sample. Palmer Penguins is a well-documented dataset and
straightforward to understand, while illustrating a realistic application of data-driven methods for classification tasks using real-world measurements. Palmer Penguins also serves as a modern alternative to the frequently-used Iris dataset, 
which originated in eugenics research and is thus not appropriate for classroom applications.

## Notebooks
Each notebook shares the same structure: loading the data and creating basic plots, setting up the classifier model with tunable hyperparameters, exploring model behavior on evaluation data with explainability methods, and assessing final 
performance with held-back testing data. The following classifier methods are available.
* **Random forests**: ``rf_class_palmerpenguins``
* **Support vector machines**: ``svm_class_palmerpenguins``
* **Neural networks**: ``nn_class_palmerpenguins`` (*in progress*--functional, but no explainability methods implemented)

## Sources and Credit
Unless specified otherwise, all code and documentation was written by [Daniel Hueholt](https://www.hueholt.earth/). Code in this project is licensed under the Open Software License 3.0 which is included with this repository as LICENSE.txt.

Check out the [official Palmer Penguins page](https://github.com/allisonhorst/palmerpenguins) at GitHub for more information (and cute penguin art!)
