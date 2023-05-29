# Signal Processing Assignment 2

This Jupyter Notebook is part of the Signal Processing Assignment 2 and 3 for UFAZ L2 S1. It includes practical and theoretical parts related to the application of exponential filtering and prediction.

## Table of Contents
- [Understanding the basics](#31---understanding-the-basics)
- [Experiment with the so-called Holt Filter](#32---experiment-with-the-so-called-holt-filter)
- [Prediction](#33---prediction)

## 3.1 - Understanding the basics

In this section, the notebook retrieves data from a previous assignment and performs a first-order difference on the dataset. It then plots the original data and the first-order difference to analyze the results.

## 3.2 - Experiment with the so-called Holt Filter

In this section, the notebook implements the Holt Filter algorithm and experiments with different values of the smoothing factor alpha. It plots the original data and the filtered data for each value of alpha, demonstrating the effect of alpha on noise reduction.

## 3.3 - Prediction

In this section, the notebook discusses various aspects related to prediction using the Holt Filter algorithm. It explains how to select the appropriate value of alpha, how to make predictions for multiple time steps ahead, and provides an implementation for prediction.

### Finding the Best Alpha

The notebook provides a function `find_best_alpha` to find the best value of alpha for the Holt Filter algorithm using Mean Absolute Error (MAE) as the evaluation metric. The function iterates over a list of alpha values and calculates the MAE for each value. It returns the alpha value with the lowest MAE as the best alpha.

### Prediction

The notebook implements a function `holt_filter_prediction` to apply the Holt Filter to a time series dataset and make predictions for a given number of months ahead. The function takes the time series data, the smoothing factor alpha, and the number of months ahead to make predictions as input. It returns a list of predictions for the specified number of months ahead.

---

This readme provides an overview of the contents and functionality of the Jupyter Notebook. For detailed implementation and code, please refer to the [Jupyter Notebook](https://colab.research.google.com/drive/1F4KBunpY7WWOGGjeBmLkKqdotExeZTRS).

Note: The notebook may require additional libraries or dependencies to run successfully.
