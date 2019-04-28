# self-training-algorithm-for-semi-supervised-learning

1- Implementing self_training with KNN, GNB, and DT classifiers
<br>2. Implementing ensemble_self using the KNN, GNB, DT classifiers:
All unlabeled data is assigned to these three categories and their predictions are compared, and if all three predictions are equal, these data are presented as the batch of the unlabeled data sets is reduced to labeled data. Then again, all three classifiers are trained with a new tagged collection, it continues until they do not agree on the label for some samples, and the data remain unlabeled. In this case, Voting is used to labeling the rest.
<br>3. Implementing kBatch_ensemble_self using the KNN, GNB, DT classifier:
This method is similar to the previous one, with the difference. The classifiers train after the k instances  get label, when k=1 means the training is sample by sample.
<br>4- In the future: Find the appropriate k using genetic optimization algorithm.
