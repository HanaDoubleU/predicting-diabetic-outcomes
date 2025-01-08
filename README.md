# predicting-diabetic-outcomes
We're predicting only diabetes with some models and analyzing them to determine which gives better results.
## proposal
https://docs.google.com/document/d/1zhVTH8ZY0tnLil2IWLUdGE66YqFnS09nXH1gsbz6l_k/edit?usp=sharing
## monday's thoughts on metrics
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
## tuesday's thoughts on metrics
* metrics for random forest classifier would classify all data in general, well.
    * after consulting xpert on the strengths of random forest classifiers and decision trees, though, i realize that it may be beneficial to create decision trees with reduced features, depending on the dataframe with important features. here are possible paths which i may follow:
    1. if the most important features are identifying factors, i may reduce the features to:
        * state
        * sex
        * agecategory
        * raceethnicitycategory
    2. if the most important features pertain to medical conditions; i may reduce the features to:
        * generalhealth
        * bmi
        * hadheartattack
        * hadangina
        * hadstroke
        * hadasthma
        * hadskincancer
        * hadcopd
        * haddeppressivedisorder
        * hadkidneydisease
        * hadarthritis
        * chestscan
        * hivtesting
        * pneumovaxever
        * htetanuslast10tdap
        * covidpos
    3. if the most important features allude to quality of life, i may reduce the features to:
        * general health
        * difficultyconcentrating
        * difficultywalking
        * difficultydressingbathing
        * difficultyerrands
        * smokerstatus
        * ecigarette usage
        * alcoholdrinkers
        * highrisklastyear
* after doing research and reading twentieth week's second day's lesson plan on svm, i realize that building an svm may be beneficial.
    * metrics should be (1) a visualization of any points overlapping with the hyperplane and (2) a classification report.
    * <mark>note for the day after tomorrow:</mark> discuss svm with latifah j..
* <mark>by the day after tomorrow, i want to finish metrics for jessica v.'s random forest classifier, and give suggestions for floris c.'s tuning.</mark>