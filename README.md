# palmerpenguins-classifiers

This repository contains notebooks to demonstrate applying different machine learning methods for classification tasks in Python. They use the Palmer Penguins dataset ([Horst et al. 2022](http://doi.org/10.32614/RJ-2022-020))
of penguin measurements taken from the Palmer Archipelago in Antarctica between 2007 and 2009. Algorithms trained on these measurements can predict the species of penguin for a given sample.  
[<img src="images/horst_penguins.png" alt="Artwork by @allison_horst showing the Palmer Penguins" width="600"/>](https://github.com/allisonhorst/palmerpenguins)    
*The three species of penguins in the dataset (artwork by @allison_horst)*

Palmer Penguins is well-documented and
straightforward to understand, while illustrating a realistic application of data-driven methods for classification tasks using field measurements. It also provides an alternative to the frequently-used Iris dataset, 
which originated in eugenics research and is thus not appropriate for classroom applications. To learn more, see the ["Stop using iris"](https://www.meganstodel.com/posts/no-to-iris/) essay by Megan Stodel and [Horst et al. 2022](http://doi.org/10.32614/RJ-2022-020).


## Notebooks
Each notebook shares the same structure: loading the data and creating basic plots, setting up the classifier model with tunable hyperparameters, exploring model behavior on evaluation data with explainability methods, and assessing final 
performance with held-back testing data. The following classifier methods are implemented, and I periodically add more as time permits.
* **Random forests**: ``rf_class_palmerpenguins`` (added Feb. 2023)
* **Support vector machines**: ``svm_class_palmerpenguins`` (added Oct. 2023)
* **Neural networks**: ``nn_class_palmerpenguins`` (added Oct. 2023, note fully functional but explainability not yet implemented)

## Credit and Links
Unless specified otherwise, all code and documentation was written by [Daniel Hueholt](https://www.hueholt.earth/). Code in this project is licensed under the Open Software License 3.0 which is included with this repository as LICENSE.txt. If you use these in a class, please reach out to let me know!

Check out the [official Palmer Penguins page](https://github.com/allisonhorst/palmerpenguins) at GitHub for more information about this dataset.

[<img src="images/horst_logo.png" alt="The Palmer Penguins logo by @allison_horst" width="250"/>](https://github.com/allisonhorst/palmerpenguins)  

*Artwork by @allison_horst*
