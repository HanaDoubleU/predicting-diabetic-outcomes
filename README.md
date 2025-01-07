# predicting-diabetic-outcomes
We're predicting only diabetes with some models and analyzing them to determine which gives better results.
## proposal
https://docs.google.com/document/d/1zhVTH8ZY0tnLil2IWLUdGE66YqFnS09nXH1gsbz6l_k/edit?usp=sharing
## monday
### current thoughts on metrics
* random forest classifier (reference: twentieth week's second day's lesson plan)
    * no score for r^2
        * r^2 can be misleading because it doesn't account for balance of data. (reference: seth's guide)
    * classification report, including (1) accuracy score and (2) confusion matrix with precision and recall.
    * visualization
        * <mark>note for tomorrow:</mark> do research on (1) which library to use and (2) how to interpret visualizations.
    * dataframe after running feature_importances_
    * <mark>note for tomorrow:</mark> do research on decision trees and svm.
    * <mark>note in general:</mark> remind floris c. to drop less important features while tuning.
* logistic regression (reference: twentieth week's first day's lesson plan)
    * no score for r^2
    * classification report, including (1) accuracy score and (2) confusion matrix with precision and recall.
