# Prediction-of-Motor-Temperature
This project is about Prediction of Motor Temperature from given data set. Here, the Motor Temperature is a combination of Rotar temperature and Stator temperature, so we need to predict two outputs at the same time

 EDA was performed. Data was analysed using Univariate, Bi-variate and Multi-variate plots.
We considered all the variables except the profile id which is the serial number to each measurement. We used Box-Cox
method to normalize the data as it was not normally distributed. In this project we predicted two outputs at a time and those
are Rotar temperature i.e. Permanent Magnet surface temperature and Stator temperature i.e Stator Yoke temperature.

We applied many machine learning algorithms and Random Forest Regressor gave the best accuracy with
R-square - 0.98.
