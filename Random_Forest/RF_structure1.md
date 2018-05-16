

### RF advantages. 

[Description](https://docs.rapidminer.com/latest/studio/operators/modeling/predictive/trees/parallel_random_forest.html)
A random forest is an ensemble of a certain number of random trees, specified by the number of trees parameter. 
These trees are created/trained on bootstrapped sub-sets of the ExampleSet provided at the Input Port. 
Each node of a tree represents a splitting rule for one specific Attribute. 
Only a sub-set of Attributes, specified with the subset ratio criterion, is considered for the splitting rule selection. 
This rule separates values in an optimal way for the selected parameter criterion. 
For classification the rule is separating values belonging to different classes, while for regression it separates them in order to reduce the error made by the estimation. The building of new nodes is repeated until the stopping criteria are met.

After generation, the random forest model can be applied to new Examples using the Apply Model Operator. Each random tree generates a prediction for each Example by following the branches of the tree in accordance to the splitting rules and evaluating the leaf. Class predictions are based on the majority of Examples, while estimations are obtained through the average of values reaching a leaf. The resulting model is a voting model of all created random trees. Since all single predictions are considered equally important, and are based on sub-sets of Examples the resulting prediction tends to vary less than the single predictions.

(A concept called **pruning** can be leveraged to reduce complexity of the model by replacing sub-trees, that only provide little predictive power with leaves. For different types of pruning refer to the parameter descriptions.)

(Extremely randomized trees are a method similar to random forest, which can be obtained by checking the split random parameter and disabling pruning. Important parameters to tune for this method are the minimal leaf size and split ratio, which can be changed after disabling guess split ratio. Good default choices for the minimal leaf size are 2 for classification and 5 for regression problems.)




### RF brief introductions.



### 
