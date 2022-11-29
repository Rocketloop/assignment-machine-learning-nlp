# Machine Learning Assignment - NLP (2-4h)

In this assignment, we will be working with an open data set available on Kaggle that contains around 200k news headlines and corresponding categories from the year 2012 to 2018. Our goal is to train a multi-class classification model that can predict the category of a news article given its headline. 

## Data

The data set can be obtained as a JSON file directly from Kaggle at https://www.kaggle.com/rmisra/news-category-dataset.

## Prediction Model 

You are free in your selection of prediction models and architecture. The input to the model should be the headline of the news article. The output should be the predicted category for the given headline. Please use a randomly sampled 80/15/5 training/validation/test split and a fixed random seed to make the results reproducible. Make sure that the model is never directly or indirectly exposed to the test set during training.   

## Evaluation

You should aim for a model with a classification accuracy of >70% on the out-of-sample test set.

## Deliverable

The following should be included in your submission:

- The runnable code used to clean and preprocess the data and train the model(s), preferably as one or multiple Jupyter Notebooks
- Documentation of your thought process in written form
- Any intermediary or derived data sets you create during this assignment
- Evaluation results for the final model(s)
