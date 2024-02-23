# Music Classification with Machine Learning

Collaborators: Sania Sufi, Valeria Briones, Maryam Shaaban, Joseph Devito and Kelsey Sniatynsky 

Datasets: https://www.kaggle.com/datasets/geomack/spotifyclassification & https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset

## Overview
In this project, we used machine learning techniques to build classifiers for determining whether we might like a song based on its attributes, which are provided by the Spotify API. We will use a dataset created by a group member to perform exploratory data analysis and implement various classifiers.

## Project Structure
Throughout the entire series, we'll:

1. **Perform Exploratory Data Analysis (EDA)** in a Jupyter Notebook using Pandas, Numpy, Matplotlib, and other commonly-used libraries.

2. **Build a Machine Learning Model** using the pycaret library to predict song likability based on its attributes.

3. **Evaluate the Model** using sklearn.

## Project Steps
1. **Exploratory Data Analysis (EDA)**
   - Performed basic EDA on the song dataset to examine its structure and gain insights into the features provided by the Spotify API.
   - Used matplotlib to create a scatter plot, histogram, and pie chart to view the relationship between two features: acousticness and danceability.
   - Used matplotlib to create a hexbin plot to view the relationship between two features: danceability and energy.

2. **Pycaret to build a machine learning model**
   - Used pycaret to set up an experiment while ignoring categorical features and string features.
   - Compared models to determine top 4 models, and then created models of each to test each model.
   - Did hyperparameter tuning to improve accuracy of the best model.
   - Attempted other optimization parameters–Ensembling and Blending–to optimize our model.

3. **Evaluate**
   - Tested the model on ~50% of the dataset to get a good mix of target values.
   - Create a confusion matrix to observe accuracy, precision, recall, and F-1 score using sklearn.


## Conclusion
We have developed, evaluated, optimized, and tested a machine learning model to create a song recommendation platform. Our model is efficient at creating a recommendation with an accuracy of >85%. After creating this algorithm, we have a comprehensive understanding of how different machine learning models can be applied to classify songs based on their attributes. This will provide valuable insights into the potential for using machine learning in other recommendation systems and related applications.
