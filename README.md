# RNA-Seq feature_selection and ML

In this repository, we employ a hybrid feature selection approach combined with machine learning to predict melanoma patients' responses to ICB therapy using RNA-Seq data. Our feature selection process includes two filter methods, univariate ROC-AUC and RliefF, along with one wrapper method, SVM-RFE. 
We achieve optimal classification accuracy through ensemble voting among five renowned machine learning classifiers.

Additionally, this repository contains code to compare different types of feature selection through three experiments:
Experiment 1: Compare four filter feature selection methods commonly used with gene expression data: univariate ROC-AUC performance, ReliefF, mutual information, and ANOVA.
Experiment 2: Evaluate feature selection methods following the initial application of the univariate ROC-AUC method, including two embedded techniques, LASSO and random forest variable importance, as well as mutual information and ReliefF methods.
Experiment 3: Compare the proposed hybrid model (univariate ROC-AUC + ReliefF + SVM-RFE) with three different combinations of feature selection techniques (univariate + SVM-RFE, ReliefF + SVM-RFE, and Mutual information + SVM-RFE).
