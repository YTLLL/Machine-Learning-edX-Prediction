# edX-Prediction
We will be looking at edX (anonymized) student data to try to predict whether a student received a certification (completed) a course. The target column is the certified column that you see in our training dataset.

Our goal is to find the model that will do best in the future by using that dataset to train the model. Instead of risking deploying a bad model into production, a great test to verify that the model will work in the future is to evaluate it based on its accuracy on data it has never seen before.

## Our goal
We will run 3 different types of classifiers for prediction.

We will visualize the ROC curves of at least 3 different classifiers on the same plot. 

## File Descriptions
This assignment uses two files

edx_train.csv - The file containing the labeled training data
edx_test.csv - The file containing the unlabeled test data that will be used to evaluate accuracy.


## Data Inputs
The training dataset and test dataset will be used to train and evaluate our model.

The data inputs are described in more detail in the edX_column_description.pdf below. We highly recommend that you read through this to understand what the columns mean.

The userId_DI field is only used for matching data point.

Note that some categorical values can have the value unk for unknown. In the numerical categories, like YoB which represents Year of Birth, -1 is filled in for unknown values.
