# house_price_prediction
## ML-Model-Flask-Deployment
This is a project in which Machine Learning Models are deployed on production using Flask API
### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.
### This is the ML model to predict the price of the houses.
### It uses linear regression model and Sklearn library
### Project Structure
This project has four major parts :
1. model.ipynb - This contains code for our Machine Learning model to predict price of houses based on training data in 'train.csv' file.
2. app.py - This contains Flask APIs that receives house details through GUI or API calls, computes the precited value based on our model and returns it.
3. templates - This folder contains the HTML template to allow user to enter house detail and displays the predicted House price.
### The data set has been included in the project
### Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://localhost:5000

You should be able to view the homepage

Enter valid numerical values in all 19 input boxes and hit Predict.

If everything goes well, you should  be able to see the predcited salary vaule on the HTML page!

