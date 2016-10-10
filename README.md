#titanic-random-forest

Predict the survival of Titanic passengers using a Random Forest model.

## About
The Titanic dataset (from Kaggle) contains information about the passengers aboard the Titanic, such as age, sex, fare cost, class and wether or not they survived the sinking of the ship.
This project implements a Random Forest classifier model to predict if passengers with unknown fates survived or perished the sinking event.

The model makes use of 10-fold cross-validation and achieves approximately ~81% accuracy. For simplification purposes, passengers with unknown age or sex data were removed from the dataset.

## Opening the project
To run the project, numpy, sklearn, and ipython notebook python packages must be installed. Refer to their respective documentation to do so.
Once these requirements are satisfied, you may run "ipython notebook" to start a notebook server where the titanic-random-forest.ipynb file can be opened.

