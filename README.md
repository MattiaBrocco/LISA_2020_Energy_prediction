# LISA_2020_Energy_prediction

In the age of smart homes, the ability to predict energy consumption not only may produce a saving, but may even result in more money generation by giving excess energy back to Grid (e.g. in the case of solar panels usage); it can furthermore be crucial to detect abnormal energy use patterns, to be part of an energy management system for load control and to model predictive control applications where the loads are needed. The aim of this study is to predict Appliance energy usage based on data collected from different sensors through regression analysis.

Four statistical regression models were trained with train/test split and measured in terms of out-of-sample accuracy: (a) multiple linear regression (b) polynomial regression (c) decision tree regressor and (d) random forest regressor. The best model (DTR), in accordance with the benchmark measure of accuracy, was able to exceed the threshold of ninety percent.

1. _Data_viz.py_: with class for plotting the four graphs on relatios and different linear models
2. _Decision_tree_opt.py_: with class for printing the parameters of evaluation for models important features for tree and forest dictionary for tuning on DecisionTreeRegressor
3. _energydata_complete.csv_ link: [https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction]
4. _linear_model_tests.py_: with class for Lasso and RFECV on linear model
5. _Project Energy Conusmption.ipynb_: main file for the project
6. _Report Energy Consumption.pdf_: 5-pages report on the activities that we have performed
7. _tunings_forest.py_: with a class used to tune parameters within the RandomForestRegessor
