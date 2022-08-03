# Fish Species Prediction
## Objective
Our objective is to create a model to predict the species of Fish based on the features like length, weight, height and width. We have made a user interactive web application using the same
model where users can input their feature details and based on those data model will analyze and predicts corresponding species of Fish. Python programming is used in this Project to develop the model and Flask and Heroku are used for the formation of web application.

## Dataset
We have used Fish.csv as the dataset for the model training. The dataset consists of 6 features- Weight, Length 1, Length 2, Length 3, Height, Width and 1 target variable which is
Species. It contains overall 159 observations including values of different species. We are using a labeled data for model training and excpet Species all other variables are numerical values.
There are 7 unique values in the target variable (Species)- Bream, Parkki, Perch, Pike, Roach, Smelt, Whitefish.

## Model
Random Forest model is used for this classification. 70% of the dataset have been reserved for the training and rest of the data for testing. During the evaluation we got the accuracy
as 66% on the test data and the prediction also worked well on the test data.

## Web Application
Heroku is a cloud platform as a service which has been used for the deployment of our model. Through web application people from anywhere can access the link and do the prediction of species.
Application is expecting the user to provide a few inputs to complete the prediction such as Height, Length1, Length2, Length3, Width and Weight. We have used html and css files for
stlying the web page. You can access the web application on the following link and checkout the prediction: https://fish-species-preds.herokuapp.com/

## Prequesite
Python setup on the local machine will be required for the execution. Latest version of sklearn package.

## Contact
For any queries contact: Akhil Mathew (mathewakhil1110@gmail.com)

