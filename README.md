# Feature-Selection-Using-Random-Forest
Random Forests are often used for feature selection in a data science workflow. The reason is because the tree-based strategies used by random forests naturally ranks by how well they improve the purity of the node. This mean decrease in impurity over all trees (called gini impurity). Nodes with the greatest decrease in impurity happen at the start of the trees, while notes with the least decrease in impurity occur at the end of trees. Thus, by pruning trees below a particular node, we can create a subset of the most important features.


In this model we will be using the famous Iris Dataset to see which features bring about the greatest prediction accuracy and how we can select the features which contrinute the most

