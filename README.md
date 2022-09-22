# UFC_Results_Modeling
Git repository for side project using historical UFC fight data. Predicting whether or not a fight will end in a KO/tKO or go the distance. Code that scrapes the data from the official UFC website http://www.ufcstats.com/statistics/events/completed is included as well.


Things to add:

* Try Feature Selection with Random Forest (with tuning and metrics in scikit-leanrn) or PCA.
* Ex: https://scikit-learn.org/stable/auto_examples/ensemble/plot_forest_importances.html
* and https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html
* Bagging (incase the random starting configurations change the minima, averaging may help)
* Try other models if NNet continues to give low performance.
* More ROC curves and conf matrices, precision recall curves, and F1 scores.
