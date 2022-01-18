# edX-Prediction
I will be looking at edX (anonymized) student data to try to predict whether a student received a certification (completed) a course. The target column is the certified column that you see in the training dataset.

The goal is to find the model that will do best in the future by using that dataset to train the model. Instead of risking deploying a bad model into production, a great test to verify that the model will work in the future is to evaluate it based on its accuracy on data it has never seen before.

## Tasks
I will run 3 different types of classifiers for prediction.

I will visualize the ROC curves of at least 3 different classifiers on the same plot. 

## File Descriptions
This assignment uses two files

edx_train.csv - The file containing the labeled training data
edx_test.csv - The file containing the unlabeled test data that will be used to evaluate accuracy.


## Data Inputs
The training dataset and test dataset will be used to train and evaluate our model.

The data inputs are described in more detail in the edX_column_description.pdf below. I highly recommend that you read through this to understand what the columns mean.

The userId_DI field is only used for matching data point.

Note that some categorical values can have the value unk for unknown. In the numerical categories, like YoB which represents Year of Birth, -1 is filled in for unknown values.

## Evaluation
The evaluation metric used for this project is classification accuracy, which is the number of correct predictions made divided by the total number of predictions.
![inbox_465647_026cc3c04afe50a03e2632d292dc3e80_eqn](https://user-images.githubusercontent.com/46210430/149876725-8d77131a-798e-4243-b0e5-2d62c5a7cae7.png)

I used unseen test dataset from kaggle and gained scores of 0.97496
