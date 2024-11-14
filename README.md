# End-end loan prediction
this is a model driven prediction, in this Notebook i am goint to be predicting wether or not somebody will get a loan approval with the data attribute given by Kaggle.

I am going to following approach:

probelm defination
Data
Feature Engineering
Evaluation
modeling

## 1. Problem defination
The competition say that i should predict with the dataset given to me, wether or not someone will get a loan approval

## 2. Data
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Loan Approval Prediction dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Files

train.csv - the training dataset; loan_status is the binary target 
test.csv - the test dataset; your objective is to predict probability of the target loan_status for each row 
sample_submission.csv - a sample submission file in the correct format

## 3. Feature Engineering¶
I was not given a data dictionary and kaggle does not ask me us to do any features engineering



## 4. Evaluating
Submissions are evaluated using area under the ROC curve using the predicted probabilities and the ground truth targets.
