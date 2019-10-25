# Algorithm comparison: SVC vs. Random Forest
----------
## The task
The task is the following: compare the performance of a Support-Vector machine for classification task (implemented by [sklearn.svm.SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)) with that of a
Random Forest (implemented by [sklearn.ensemble.ExtraTreesClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html)).  
<br> I also tried to optimize both algorithms' parameters and determine which one is best for this dataset. <br>
At the end of the analysis, I chose an algorithm and its optimal set of parameters: this choice is written explicitly at the end of the notebook.

## The dataset
The dataset is composed of 1100 samples with 31 features each. The first column
in the dataset represents the label. There are 5 labels. The remaining columns
are numeric features, except for the last column which is categorical (with 3
categories).

