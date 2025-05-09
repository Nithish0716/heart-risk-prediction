This Python script predicts heart disease risk using patient health data with the K-Means clustering algorithm.

It begins by importing necessary libraries like pandas, numpy, matplotlib, and scikit-learn.

The heart disease dataset (heart.csv) is loaded, cleaned, and selected features are extracted.

Features such as Age, Cholesterol, RestingBP, MaxHR, and Oldpeak are standardized using StandardScaler.

K-Means clustering (with 2 clusters) is applied to group patients into potential risk categories.

A dynamic risk_map labels each cluster as either "High Risk" or "Low Risk" based on heart disease prevalence.

The predict_risk function collects user input on health metrics to assess their risk.

It scales the input, predicts the cluster, and calculates the user's heart disease probability.

Depending on the cluster, the script gives a health warning or reassurance with advice.

Optionally
