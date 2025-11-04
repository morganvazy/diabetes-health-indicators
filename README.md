# diabetes-health-indicators
TLDR: Python program that reads a csv and cleans, analyzes, and visualizes a diabetes and health indicators dataset. This program uses mathplotlib.pyplot, numpy, and pandas.
Full README:
Analyzing the Diabetes Health Indicators Dataset 

Morgan Vasiliou 

 

This program reads a csv file containing data on diabetes diagnoses and lifestyle habits, cleans that data, and analyzes it with accompanying visuals. This file employs many functions to separate the data frame into many smaller data frames to create many different visuals such as a bar graph, a heat map, and histograms. This program creates the named visuals and outputs the percentages of females and males with diabetes using the function diabetes_and_gender_percent(cleaned_data). Additionally, it will output the mean and standard deviation of a subset of the data with the function mean_and_standard_deviation(data, column). The user is not asked for any inputs because the file uses a csv named diabetes_012_health_indicators_BRFSS2015. Link to this dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset  

To compile: python diabetes_data_analysis.py 

Source: This code was written by Morgan Vasiliou. The function display_heat_map(percent_dict) is structured on matplotlib’s annotated heatmap documentation. 
