# Assignment-1-CS465

#Predicting Miles per Gallon using Linear Regression

This project uses linear regression to predict miles per gallon (mpg) for a dataset of cars based on different predictor variables such as weight, horsepower, and displacement.

# Dataset

The dataset used in this project is the mtcars dataset from the R programming language. The dataset contains 32 observations of different cars, with 11 variables including mpg, cyl (number of cylinders), disp (displacement), hp (horsepower), drat (rear axle ratio), wt (weight), qsec (quarter-mile time), vs (V/S), am (automatic or manual transmission), gear (number of forward gears), and carb (number of carburetors).

# Project Structure

The project consists of the following files:

linear_regression.ipynb: a Jupyter notebook that contains the main code for the linear regression analysis.
mtcars.csv: the dataset used in the analysis.
README.md: this file, providing an overview of the project.

#Dependencies

The following libraries were used in this project:

pandas
numpy
matplotlib
seaborn
sklearn

# Usage

To run this project, you will need to have Jupyter Notebook installed, as well as the libraries listed above. Clone the repository and navigate to the project directory in your terminal. Then, type jupyter notebook to launch Jupyter Notebook. Open the linear_regression.ipynb file and run the cells in order to reproduce the analysis and results.

# Results
The analysis showed that weight and horsepower are strong predictors of miles per gallon in cars. Adding displacement as a third predictor improved the model slightly, but not significantly. The mean squared error for the testing set decreased from 12.48 in the simple linear regression model to 8.47 in the multiple linear regression model. However, including all three predictors did not improve the model much compared to just using weight and horsepower as predictors.

# Acknowledgements
This project was completed as part of a Machine Learning course at Prince Sultan University.
