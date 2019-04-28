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
* Hidden layer 1: 2048 nodes (15% dropout)
* Hidden layer 2: 1024 nodes (5% dropout)
* Hidden layer 3: 512 nodes 

### Epoch selection
* Early stopping was implemented to obtain optimal epoch (5)

## Performance

### Trained Model Performance

* Loss Curve for training and validation set
<img src='https://i.ibb.co/zrR72pc/loss.png'>

* Area under ROC
<img src='https://i.ibb.co/2Sh689q/roccurve.png'>
 
* Precision for Model : 0.65
* Sensitivity/Recall for Model : 0.89
* F1 Score for Model : 0.75
* F-Beta Score for Model : 0.83
 
### Cross validation Performance
10-fold cross validation summary metrics (Average)

* Precision for Model : 0.67
* Sensitivity/Recall for Model : 0.93
* F1 Score for Model : 0.77
* F-Beta Score for Model : 0.85
* AUC for Model : 0.96
 
