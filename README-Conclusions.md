# Classification_hw

## Credit Risk Resampling

1) The balanced accuracy score, which should be used, as is the case with loan status data, if there is an imbalanced split between the two binary classes, identifies the ratio of ture positive and negative calls that the model identified. The model with the best (highest) balanced accuracy score is Random Oversampling model. Overall, oversampling (the Random Oversampling and SMOTE model) performed better than their undersampling counterparts.

2) Recall, another measure of classification strength, measures how many true positives a model identifies out of all of the positives, taking into account the false negatives. The model with the highest recall is SMOTE with a 0.88 recall ratio.

3) The geometric mean (G-mean) is the root of the product of class-wise sensitivity. This measure tries to maximize the accuracy on each of the classes while keeping these accuracies balanced. The model(s) with the best geometric mean are the Random Oversampler and the ClusterCentroids resamplers, with a mean score of 0.79.

## Credit Risk Ensemble

1) The model with the best balanced accuracy score is the Easy Ensemble Classifier. This model uses boosting to train weak learners sequentially by learning from the mistakes of previous learners. 

2) Both models, the Easy Ensemble Classifier and the Balanced Random Forest Classifier, had identical recall scores between them. This takes into account both high and low risk loan applicants. 

3) Both models have identical geometric mean scores.

4) total_rec_prncp,total_pymnt, and total_pymnt_inv are the three most import features.