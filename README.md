# House Prices Prediction Model

![suburban houses](https://th.bing.com/th/id/R.5a336a32ca043cce70ce6c95a5c15241?rik=47sFZzeTwfvA0Q&riu=http%3a%2f%2fi.huffpost.com%2fgen%2f1549193%2fimages%2fo-SUBURBS-facebook.jpg&ehk=YcIWot3xsVpiv9DvZLg4sl4rnrloUJ%2bGM2vtBsH%2fmTQ%3d&risl=&pid=ImgRaw&r=0)

**To see the final fruits of this project: check out my [Kaggle notebook](https://www.kaggle.com/code/rajpulapakura/houses-prices-prediction-model)!**

From the height of the basement ceiling to the area of the porch, there are numerous factors that come into play when determining the price of a house. This project aims to build a regression model which predicts the prices of residential homes in Ames, Iowa.

## Source materials

The source materials for this project come from a [Kaggle competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview):

There are 3 files provided:

1. *train.csv*: The training dataset contains 79 explanatory variables, ranging from the roofing material to the area of the living room, along with the target variable "SalePrice". 
2. *test.csv*: The testing dataset also contains 79 features but no target variable. This is the dataset from which we draw predictions.
3. *data_description.txt*: This file contains detailed descriptions about the features of the dataset.

## Project Overview

In this project, we go through the following topics:

- Dataset cleaning: This involves imputing null values, fixing data types and removing outliers.
- EDA (Exploratory Data Analysis): We analyse the distributions of the features as well as their correlations with each other and the target variable (SalePrice)
- Feature engineering/selection: We perform in-depth feature extraction
- Modelling: We test out 5 different models and use GridSearch to find the optimal parameters for each. Then we choose the best model and use that to make our final predictions.

Throughout the project there is clear documentation and comments to make your journey much more enjoyable.

## Project Files

In this repository you will find 7 files:

- *train.csv*: training dataset
- *test.csv*: testing dataset
- *data_description.txt*: information about the features of the dataset
- *predictions.csv*: the predictions generated from the model
- *README.md*: the file you are reading rn
- *House Prices Prediction Version 1.ipynb*: first iteration
- *House Prices Prediction Version 2.ipynb*: final iteration

### Notebook Versioning

There are two versions of the project notebook.

*House Prices Prediction Version 1.ipynb* is the first iteration of the project. It contains the complete data analysis and testing. It is not as organised and cohesive as the second version, so I recommend going through the second version first.

*House Prices Prediction Version 2.ipynb* is the condensed second iteration of the project. It utilises sklearn Pipelines to automate and orgainse the different sections of the project. This version is also much better documented and code is organised into classes to improve readability. **I recommend going through this file first**, and then going through the first version to get a deeper understanding of the methods I used in this version.

## Let's go!

Now that you understand the ins and outs of the project, it's your time to get into it and play around with it. I strongly encourage you to clone this repository (or download it) and try out different models or data anaylses.

I would also love to hear any feedback/suggestions you have for the project. If you do have suggestions, I have created a [Kaggle notebook](https://www.kaggle.com/code/rajpulapakura/houses-prices-prediction-model) which is a copy of *House Prices Prediction Version 2.ipynb*. Please go to this page and comment on it, so I can read your invaluable feedback/praise!

Thank you so much for taking the time to read through this project.

Cheers!
