Get familiar with data in "default.csv" and "default_balanced_training.csv" (description of features can be found in "linear and logistic regression part2"); Write a jupyter notebook in which you

- Use various feature combinations to fit a logistic regression model on data in   
  "default_balanced_training.csv", aiming at having high accuracy
- Use the original data from default.csv, repeat the previous step and try different 
  regularizations and values for C, with weighted accuracy (sklearn.metrics.accuracy_score's sample_weight parameter), precision and F1-score
- Use "predict_proba" method to make probability prediction and compute log loss, change feature   combination to find the best log loss (smallest)

For all evaluation, divide the data set into a training set with 80% randomly drawn samples and a test set with the rest samples. Train the classifier on the former and test and record the performance on the latter. For each step, conclude with a selection of features and report prediction scores.