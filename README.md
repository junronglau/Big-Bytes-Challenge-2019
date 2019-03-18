# Big Bytes Challenge 2019
Submission for Cognizant's hackathon. Details of the challenge can be found at: http://bigbytes.sg/the-mission/  <br/>
Dataset can be found at: https://www.dropbox.com/s/fiugsupsw12tnda/Credit%20Card%20Dataset%20for%20Students.zip?dl=0

## Objective
The proposed solution to improving fraud recovery through the early identification and proactive management of suspicious transactions by a Neural Network trained on the provided dataset. 

## Methodology

### Data preparation
* Random Oversampling on minority class 0 for training data set
* 80% Training and 20% Testing split
* Standardizing of features
   
### NN Architecture
* Hidden layer 1: 2048 nodes 
* Hidden layer 2: 1024 nodes 
* Hidden layer 3: 512 nodes 

## Performance

### Trained Model Performance

* Loss Curve for training and validation set
<img src='https://i.ibb.co/3pb9pD4/Losscurve.png'>

* Area under ROC
<img src='https://i.ibb.co/hBn7d00/roc.png'>
 
* Precision for Model : 0.79
* Sensitivity/Recall for Model : 0.89
* F1 Score for Model : 0.83
* F-Beta Score for Model : 0.87
 
### Cross validation Performance
6-fold cross validation summary metrics (Average)

* Precision for Model : 0.75
* Sensitivity/Recall for Model : 0.89
* F1 Score for Model : 0.8
* F-Beta Score for Model : 0.85
* AUC for Model : 0.94
 
