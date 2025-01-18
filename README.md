# module-8
UCB-ML Module 8: Feature Engineering and Overfitting

## TODO: 
- look at quantile tranformations
- review use of TransformTargetRegressor in scikit-learn
- review use of Permutation Feature importance API in scikit-learn

## Review use of Permutation Feature Importance API in scikitlearn 
This measures the contribution of a feature to a model by shuffling a single feature and then observing the resulting degradation of 
the model's score using the MSE for example. If a seriouse degradation occurs then that suggests that the feature is of importance to 
the model's performance.