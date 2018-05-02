# ml-trees-pt2

## Bagged trees 
- Not just one tree, but a combination of several trees 

## Random Forests 
- Similar to bagged trees, but only a random subset of features is used in each split in a decision tree. In bagging, all features are used.

## Boosting methods (more applied)
- Iteratively fitting trees by updating weights of each observation, depending on how difficult it is they classify
- Prediction = weighted sum of predictions by previous tree models
- Gradient boosting: shortcomings by adding gradients in the loss function (Unit 2 in module 3 covers gradient descent)
  --> use of the gradient boosting technique results in models that strictly outperform random forests most of the time"
