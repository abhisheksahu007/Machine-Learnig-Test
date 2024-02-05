# Machine-Learning-Test
This repository contains a test model based on prediction using Machine Learning.
In this project, we have combined historical usage patterns with weather data in order to predict bike rental demand.

Following datasets have been used in this project for prediction of bike rental demand:

train.csv : Use this dataset to train the model. This file contains all the weather related 
            features as well as the target variable “count”. Train dataset is comprised of first 
            18 months.

 test.csv : Use the trained model to predict the count of total rentals for each hour during the 
           next 6 months.

Following files have been uploaded in this repository for the ease of understanding of this project on "Machine Learnning":
    1) About_Test_Problem.txt- This text files contains details about the project.
    2) train.csv- This csv file contains the dataset on which the model is trained.
    3) test.csv- This csv file  contains the dataset on which the model is used to predict the bike rental demand.
    4) Machine Learning Test Compiled.ipynb- This ipynb file contains the notebook having the all the EDA(Exploratory Data Analysis) on the raw data and various models used to check their accuracy and               finally the best model is chosen.
    5) Using Best Model to predict data.ipynb- This ipynb file containt the notebook in which the best model is used to predict the output on the test dataset.
    6) Bike Rental Predicted.csv- This csv file contains the predicted bike rental demand. It has only two columns "datetime" and "Predicted count".
