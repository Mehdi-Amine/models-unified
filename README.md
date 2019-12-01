# models-unified
Code implementation and examples for my article on Medium about Ensemble Methods

Provided you have already built a couple decent predictors, think about combining them into an Ensemble predictor. Bear in mind that an Ensemble works best when its individual predictors are different from one another. To introduce diversity you can: 
* Use a different training algorithm for each predictor. 
* Bagging / Pasting: Use the same training algorithm for all predictors but fit each on a different subset of the training instances. 
* Random Subspaces method: Use the same training algorithm for all predictors but fit each on a different subset of the features. 
* Random Patches method: Use the same training algorithm for all predictors but fit each on a different subset of the features and instances. 
