# My First Machine Learning Project

## Overview

I started learning Machine Learning with the book [‘Hands-On Machine Learning with Scikit-Learn & TensorFlow’](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) by Aurélien Géron. After reading this book, I wanted to implement what I learned, so I decided to participate in [this Kaggle competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

The competition involves predicting house prices based on [79 explanatory variables](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) that describe almost every aspect of residential homes in Ames, Iowa.

## Project Description

	- data_description : Dataset Description   .
	- house_pricing : Jupyter notebook for data exploration, analysis, data cleaning and model building.
    - train : data to train model
    - test : data to validate model

## Results and Learnings

### Results

Model Performance with cross-validation:

	- RMSE Mean: 32 618.82$
	- Standard Deviation: 7 207.65$
    - median sale price : 163 000$

Final Submission:

	- Ranking: 3660 out of 4,897

### Thoughts and Learnings

Challenges:

	- As my first ML project, I had to familiarize myself with libraries like pandas and scikit-learn.
	- The most challenging part was cleaning the data because I created my own transformer to return a DataFrame instead of an ndarray.
Techniques Used:

	- I compared three different regression models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor.
	- Linear Regression was underfitting, Decision Tree Regressor was overfitting, and Random Forest Regressor performed the best.

## Future Improvements

- Model Improvements

	- Hyperparameter Tuning: Implement more sophisticated hyperparameter tuning techniques, such as Grid Search or Random Search, to optimize the performance of the models.

- Testing Additional Models
    - Neural Networks: I plan to dive into deep learning by implementing neural network models using frameworks like TensorFlow or PyTorch. This area fascinates me, and I’m excited to deepen my understanding of it
