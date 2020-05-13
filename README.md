<h1 align="center"> Machine Learning project </h1>

## Project: Predicting Boston Housing Prices


### Project Overview
In this project, I have applied basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. We first explored the data to obtain important features and descriptive statistics about the dataset. Next, we properly split the data into testing and training subsets, and determined a suitable performance metric for this problem. We then analyzed performance graphs for a learning algorithm with varying parameters and training set sizes. This enabled us to pick the optimal model that best generalizes for unseen data. Finally, we tested this optimal model on a new sample and compared the predicted selling price to our statistics.

### Description
The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with our peers, we decide to leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. Luckily, we\'ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Our task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for our clients\' homes.


### Software and Libraries

This project uses **Python** and the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://ipython.org/notebook.html).


### Code

The project mainly contains three files:
- `boston_housing.ipynb`: This is the main file where I have performed my work on the project.
- `housing.csv`: The project dataset. We loaded this data in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
