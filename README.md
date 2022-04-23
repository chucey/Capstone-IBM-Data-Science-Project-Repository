# Capstone-IBM-Data-Science-Project-Repository
This repository highlights the work completed as part of the IBM Data Science Professional Certificate.

This project required me to pretend to be a data scientist who is working for a corporate competitor of SpaceX with the goal of launching rockets as cheaply as posiible. To do this, I was tasked with building a machine learning model that could predict successful rocket landings after launch. If I can predict a successful landing, I can then determine the cost of launching a rocket.

To begin, I gathered data of past SpaceX rocket launches via the SpaceX API and via webscaping. Refer to my "Data Collection API Notebook" and my "Data Collection with Web Scaping Notebook" for more details. Gathered data included:
* launch site of each rocket
* mass of each rocket's payload
* type of booster rocket used
* type of landing (successful or failed)
* etc

After data gathering, I performed some exploratory data analysis (EDA) to not only clean the data but to also better understand it. Please refer to my "EDA" and "EDA with Data Visualizations" notebooks for more details.

Subsequently, I created several data visualizations in order to identify any trends or relationships in the data. I used the Folium library to visualize the data in my "Interactive Visual Analytics" jupyter notebook, and I built a dash application to display dynamic visuals.

Next, I created a machine learning model that could predict the outcome of future launches. As part of the analysis, I split my data into a training and a testing set and used my training set to train four separate machine learning algorithms:
* k nearest neighbour
* decision tree
* support vector machine
* logistic regression

I fine tuned each model using the gridSearchCV() function. and evlauted the accuracy of each model using the R^2 score.

Please feel free to read my "Machine Learning Prediction Notebook" for more details.
