# MachineLearning-LABs-and-HWs
This includes all my HWs related to the Machine Learning course at my home university.

Lab 1: Matrix Profile & Time-Series Anomaly Detection

Covers:

Basics of subsequences and sliding windows

Z-normalization of time series

Computing distance profiles

Matrix Profile creation

Detecting discords (anomalous subsequences)

Main idea: Find unusual patterns in a time series by comparing every subsequence to every other subsequence.


Lab 2: Elastic Distance Measures (DTW, WDTW)

Covers:

Dynamic Time Warping (DTW) distance

Handling misaligned sequences in time

Weighted DTW (warping penalty based on alignment distance)

Generic cost-function-based DP implementation

Main idea: Measure similarity when sequences may stretch/shift in time (common in real motion/sensor data).


Lab 3: Time-Series Forecasting With Machine Learning

Covers:

Creating lagged input features from historical values

Including exogenous inputs (external variables)

Training a regression model for forecasting

Iterative multi-step forecasting (rolling predictions)

Main idea: Reframe time-series prediction as a supervised ML problem.


Lab 4: Feature Engineering / Classification

Since not shown, but typically next step in such a course:
Covers:

Time-series classification tasks

Feature extraction or shape-based distances

Using DTW or statistical features to classify sequences

Main idea: Identify what pattern a given time series belongs to.


Lab 5: Model Evaluation & Real-World Application

Based on progression:
Covers:

Evaluating forecasting performance (e.g., MAE, RMSE)

Validation techniques for time series (rolling/blocked CV)

Applying learned methods to a real-world dataset

Comparing classical vs. elastic vs. ML approaches

Main idea: Put everything together and measure what actually works well.
