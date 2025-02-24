# Employee_BurnRate_Prediction_Model
Predicting employee burnout using data-driven models is essential for proactive intervention, allowing organizations to implement targeted support strategies, foster a healthier work culture, and sustain long-term productivity.This project aims to build and compare the performance of several regression machine learning model to predict employee burnout rate from data such as gender, hours worked per day, designation, and the like.

Table of Contents
## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Data](#data)
3. [Model Architecture](#model-architecture)
4. [Evaluation](#evaluation)
5. [Model Performance](#model-performance)
6. [Contributing](#contributing)
7. [Contact Information](#contact-information)

## 1. Problem Statement
Today, burnout is often described as 'The Great Exhaustion' because according to a study published by Mercer in 2024, 8 out of 10 employees are at risk of burnout. It thus comes as no surprise that HR departments are very interested in monitoring their employees' burnout rate. Without early detection, burnout often results in increased absenteeism, higher turnover rates, and a steep rise in recruitment and training costs, ultimately undermining the organization's competitive edge Understanding and predicting employee burnout rates with machine learning can provide organizations with the right insights to create supportive and healthy environments in the workplace as well as sustain long-tern prodductivity.

## 2.Data
The dataset used for this project consists of HR Analytics data including, when an employee joined the company, there level in the company, gender, whether work from home options are available, their mental fatigue score, among other features and the target variable, the burn out rate.

 
## 4. Evaluation 
During training, each model was evaluated based on pixel accuracy, that is the percentage of pixels in the image which were correctly classified either as forested or non-forested areas. After hyperparameter tuning, the best performing model was then evaluated based on both accuracy and intersection over union.

## 5. Model Performance
#### Performance of the FCN model
The validation loss is higher than the train test loss,that is expected because validation data is unseen to the model. However, that would be a sign of overfitting. The achieved accuracy for the FCN model was 77%.

<img src="./Results/FCN_learningcurves.png" alt="Learning curve of the FCN" width="350"/>

#### Performance of the Unet Model
The training and validation loss curves are tracking each other closely, meaning there is no significant over-fitting and the model is generalizing well.
The achieved accuracy before hyperparameter tuning was 79%.

<img src="./Results/Unet_learningcurves.png" alt="Learning curve of the FCN" width="350"/>


## 6. Contributing
1. Fork & clone the repo locally
2. Create a new branch
3. Make changes on your branch
4. Open a pull request and submit your work for review
   
## 7. Contact Information
Please reach me via email at: mwangi25.mercy@gmail.com



