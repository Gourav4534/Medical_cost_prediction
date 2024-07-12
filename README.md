<<<<<<< HEAD
# Medical_cost_prediction
=======
# Medical Cost Prediction
Predicting medical costs of individuals based on different features using several ML (Regression) algorithms. The application was deployed on AWS EC2 through AWS ECR (Dockerized Container).

## Dataset
The [Medical Cost Prediction](https://www.kaggle.com/datasets/mirichoi0218/insurance) consists of around 1300 records and six independent variables along with ``charges`` target  variable:

1) ``age``: Age of the individual
   
3) ``children``: Number of children the individual has
   
5) ``bmi``: Body Mass Index of the individual - where bmi <18.5 falls under underweight range, 18.5 - 24.9 falls under normal range, 25.0 - 29.9 falls under overweight range, and >30.0 falls under obese range
   
7) ``sex``: Sex of the individual - Male or Female
   
9) ``smoking``: Whether the individual is a smoker or not
    
11) ``region``: What region the individual belongs to - Northeast, Northwest, Southeast, Southwest

## Getting Started (Cloning)
Clone the repo using 
```
git clone https://github.com/NvkAnirudh/Medical_Cost_Prediction.git
```
## Installing 
Install the required packages from ``requirements.txt`` after commenting out ``-e .`` which runs ``setup.py`` automatically.
```
pip install -r requirements.txt
```
## Usage
1) Once cloned, run the ``data_ingestion.py`` script to load, transform, and train different ML algorithms (Regression) on loaded data. This script creates all the required artifacts (train, test, and validation data, model, and preprocessor pickle files).

Model.pkl will have the best model with the best parameters from different models used.
```
python src/components/data_ingestion.py
``` 
2) After the training, run the test script ``test.py`` in the Tests folder to get the r2 score from the best model on test data.
```
python Tests/test.py
```
3) Run the ``application.py`` which is a Flask application to get the required UI locally.
```
python application.py
```
And, that's it, the application should run perfectly locally, and you can test the UI out and play with it.


## Authors   
- Gourav Yadav
