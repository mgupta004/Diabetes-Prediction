# Diabetes-Prediction


## Overview
In this project, we implemented several machine learning techniques to predict diabetes using different classifiers. Here's a summary of our findings:

## Results Summary

### K-Nearest Neighbors (KNN)
- Achieved an accuracy of 79% on the training set and 78% on the test set.

### Decision Tree Classifier
- Initially achieved 100% accuracy on the training set but dropped to 71% on the test set, indicating overfitting.
- Applied pre-pruning to the decision tree, resulting in 77.3% accuracy on the training set and 74% on the test set.

### Multilayer Perceptrons (MLP)
- Achieved an accuracy of 82% on the training set and 80% on the test set.

## Conclusion
Overall, the KNN and MLP models performed relatively well compared to the decision tree classifier, which suffered from overfitting despite attempts to mitigate it through pre-pruning.

## Next Steps
Further investigation could involve:
- Fine-tuning hyperparameters of KNN and MLP models.
- Exploring ensemble methods to improve predictive performance.
- Collecting additional relevant features to enhance model accuracy.



