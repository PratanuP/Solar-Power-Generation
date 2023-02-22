# Solar-Power-Generation
A solar power generation company wants to optimize solar power production.

Factors affecting Solar Power Generation

Introduction:
A solar power generation company wants to optimize solar power production.
It is an operational project intended to optimize, increase efficiency, take precautions, reduce costs for power delivery without much difficulty.

Dataset:

The dataset contains the following columns:
['Year', 'Month', 'Day', 'Hour', 'Minute', 'Temperature', 'Clearsky DHI', 'Clearsky DNI', 'Clearsky GHI', 'Cloud Type', 'Dew Point', 'Fill Flag', 'Relative Humidity', 'Solar Zenith Angle', 'Pressure', 'Precipitable Water', 'Wind Direction', 'Wind Speed']
The given data is of ten years at an interval of every 30 mins.

Objective:

The objective is to predict the ‘Clearsky DHI’, ‘Clearsky DNI’, ‘Clearsky GHI’ of year 2019 from the given dataset from the year 2009-2018


Methodology:

There are various factors which affect the solar power generation.
Some data columns are highly correlated to other columns, displayed using heatmap.
The relation graphs are plotted to display the relationship between two columns using bar plot.
As there are three target variables to be predicted, we will try to predict them one by one. We tried to use one or two target(s) as feature(s) for another target.
Then used various supervised learning algorithms like Linear Regression, Decision Tree Classifier, Extreme Gradient Boosting Regression to train, test and evaluate the built model.

Inference:

Extreme Gradient Boosting ‘XGBRegressor()’ had the least error while predicting the ‘Clearsky DHI’, ‘Clearsky DNI’ and ‘Clearsky GHI’.

Future Scope:

a)Improvement of the prediction technique that would reduce errors.
b)More Factors can come into play with the advancement of technology.

Conclusion:

My model has tried to predict the factors that affect solar power generation and may have detected some flaws in the system.
