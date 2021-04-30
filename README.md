# Unit 11—Risky Business

![Credit Risk](Images/credit-risk.jpg)

## Background

Auto loans, mortgages, student loans, debt consolidation ... these are just a few examples of credit and loans that people are seeking online. Peer-to-peer lending services such as LendingClub or Prosper allow investors to loan other people money without the use of a bank. However, investors always want to mitigate risk, so you have been asked by a client to help them use machine learning techniques to predict credit risk.

I was tasked to build and evaluate several machine-learning models to predict credit risk using free data from LendingClub. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so different techniques for training and evaluating models with imbalanced classes were applied. 
## i had different results than the what the homework answers returned

#### Resampling
BRF: 78% accurate for telling us whether someone is low risk or high risk
The precision which tells us false positive was low
BRF and EEC gave us the exact same data; telling us that neither model is better or worse, thought the accuracy was slightly better for EEC (not looking at the original hw data)
We are getting more false negatives; but we do have 91% true negatives (so it predicts low_risk better)

#### Ensemble Learning

Oversampling/undersampling:
Oversampling was more accurate than undersampling but only by small percentage;  Combination model had a high accuracy; All models had poor precision, but better recall  and could determine negatives better; combination model was poor for both recall and precision.

Top 3 features were total_rec_prncp, total_rec_int and total_pymnt_inv

---



---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
