# Comparison of Support Vector Machine and Linear Regression (Classical ML) 




Train two classifier methods and compare the results.
Had taken Support Vector Machine (SVM) and Linear Regression (LR).


Dataset: Kaggle - Traffic, Driving Style and Road Surface Condition.





## Results of models:

Accuracy SVM/LR = 0.78/0.77;

Balanced Accuracy SVM/LR = 0.73/0.71;

F1-Score Breakdown SVM/LR = 0.86/0.85;


### Label proportions for each variable

![Results](https://github.com/GusevPortfolio/Comparison-of-SVM-and-LR-in-ML/blob/main/Visualisation/Results%201.PNG)


### Accuracy & Balanced Accuracy for models trained on each target

![Results](https://github.com/GusevPortfolio/Comparison-of-SVM-and-LR-in-ML/blob/main/Visualisation/Results%202.PNG)


### F1-Score Breakdown for Road Surface

![Results](https://github.com/GusevPortfolio/Comparison-of-SVM-and-LR-in-ML/blob/main/Visualisation/Results%203.PNG)






## Conclusions:

The imbalance of different labels in the target variables effected the classifiers accuracy and balanced accuracy. While the more unbalanced target variables showed higher accuracy, they also showed lower balanced accuracy, indicating that the classifiers were doing a poor job of classifying less frequently encountered labels. The F1 score more starkly reflects the poor precision and recall with the imbalanced data.

The SVM and Logistic Regression approaches are remarkably similar, and it's normal that the metrics gap is minimal. The low gap of metrics is a consequence of different approaches to the loss function or that the SVM considers only points near the local boundary, while logistic regression considers global ones. In a situation with more balanced data, it could show bigger gaps in two methods metrics.

Improvements of models strongly depend on the quality and size of data. The results of the Linear Regression and Support Vector Machine models above, show a capacity for deployment in non-safety related functions. Further research into more complex models and hyperparameter optimization could yield a model more suited to compensate for imbalances in training data.



### Additional gratitude to my project team:
Davin Mc Gowan,
Rabin Sapkota, 
Senan Stanley;
