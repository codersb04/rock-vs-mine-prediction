# rock-vs-mine-prediction
## Task: </br>
Predicting whether the material detected is a rock or a mine
## Dataset: </br>
The dataset has been taken from UCI Repository. It consists of 208 sets of records with 61 features and the last 61st feature depicts whether it is a rock(R) or mine(M). The dataset is attached to this repository.
## Building Model:</br>
The steps involved in creating the model are:</br>
<b> Importing the Libraries: </b><br/>
Libraries needed for running the projects are NumPy, pandas, and sklearn and from sklearn, we import Logistic Regression and accuracy score</br>
<b> Data Collection and Data Processing:</b><br/>
We can import the dataset you read_csv function of pandas. We can make use of functions such as describe, shape, value_counts, groupby etc. to know more about the type and content of our datasets.</br>
<b> Dividing the dataset as training and testing dataset:</b><br/>
The first step to this would be separating the target feature from the dataset i.e the feature which depicts whether the element is rock(R) or mine(M)<br/>
Next, we will split the 2 sets of datasets into training and testing using <b> train_test_split</b> function.</br>
<b>Model Training: </b><br/>
I am going to use <b>Logistic Regression</b> Algorithm for building the model.</br>
Logistic Regression is a machine learning algorithm which is used in prediction when the dataset is in the form of a categorical dependent variable. </br>
<b>Model Evaluation:</b></br>
Here I have predicted the model for trained data and test data and the accuracy score comes out to be 83% and 76% respectively.</br>

Reference: Project 1 : SONAR Rock vs Mine Prediction with Python | End To End Python Machine Learning Project, 
Siddhardhan, https://www.youtube.com/watch?v=fiz1ORTBGpY&list=PLfFghEzKVmjvuSA67LszN1dZ-Dd_pkus6




