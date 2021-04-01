# Caesarian Section Classification Dataset
---
## [Link](https://archive.ics.uci.edu/ml/datasets/Caesarian+Section+Classification+Dataset)

## Data Set Information:
This study examined the need for a caesarean section based on health outcomes.

## Source:

Name: Muhammad Zain Amin
Email: ZainAmin1 '@' outlook.com
Institution: University of Engineering and Technology, Lahore, Pakistan

Name: Amir Ali
Email: amirali.ryk1 '@' gmail.com
Institution: University of Engineering and Technology, Lahore, Pakistan

## Attribute Information:

We choose age, delivery number, delivery time, blood pressure and heart status.
We classify delivery time to Premature, Timely and Latecomer. As like the delivery time we consider blood pressure in three statuses of Low, Normal and High moods. Heart Problem is classified as apt and inept.

@attribute 'Age' { 22, 26, 28, 27, 32, 36, 33, 23, 20, 29, 25, 37, 24, 18, 30, 40, 31, 19, 21, 35, 17, 38 }
@attribute 'Delivery number' { 1,2,3,4 }
@attribute 'Delivery time' { 0,1,2 } -> {0 = timely , 1 = premature , 2 = latecomer}
@attribute 'Blood of Pressure' { 2,1,0 } -> {0 = low , 1 = normal , 2 = high }
@attribute 'Heart Problem' { 1,0 } -> {0 = apt, 1 = inept }

@attribute Caesarian { 0,1 } -> {0 = No, 1 = Yes }

## Relevant Papers:

M.Zain Amin, Amir Ali.'Performance Evaluation of Supervised Machine Learning Classifiers for Predicting Healthcare Operational Decisions'.Machine Learning for Operational Decision Making, Wavy Artificial Intelligence Research Foundation, Pakistan, 2018