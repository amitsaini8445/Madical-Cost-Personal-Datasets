# About tha data
how much you pay for health insurance are not within your control.There are some factors that affect how much health insurance cost.
This dataset contains person's information like age,sex,gender,bmi,region,smoke or not and we have to predict their medical insurance
cost.In this notebook I will apply regression techniques of supervised learning to predict the medical insurance costs.

Columns

age: age of primary beneficiary

sex: insurance contractor gender, female, male

bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

children: Number of children covered by health insurance / Number of dependents

smoker: Smoking

region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

charges: Individual medical costs billed by health insurance

Problem :
Predict the insurance cost (accurately)

## Pipeline to solve the problem:
1. Import the library
2. load the data
3. EDA
  - Missing value
  - outlier treatement
  - normalization and scaling
  - Encoding categorical feature
  - Bivariate analysis
4. Split the data into depndent and independent feature
5. split the data into train and test data
6. Apply the machine learning model
7. Find the accuracy of the model
8. Predict the data

## Conclusion :
I have got the accuracy of the training and testing data  85% and 83% . Here there are not overfitting problem.  

