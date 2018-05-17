## my result writing

- say that RF is already used in econometrics.

:smile: Random forest (Dietterich, 2000; Breiman, 2001) is a machine learning algorithm, which begins to receive more and more attention in econometrics, for example, in GDP forecasting and poverty predictions (see, e.g., Otok and Seftiana (2014), Thoplan (2014), Sohnesen and Stender (2016)). 

- RF works in this way...  and examples of RF in our context.

The basic idea of random forest is decision tree, which uses a set of observed predictors to recursively partition the data until the values of the dependent variable become homogeneous with each sub-partition. 
Random forest is an ensemble of decision trees. Each decision tree is created by using a subset of the attributes used to classify a given population. Those decision trees vote on how to classify a given instance of input data, and the random forest bootstraps those votes to choose the best prediction. 

It creates a forest (many decision trees) and orders their nodes and splits randomly. The more trees in the forest, the better the results it can produce. 

Each node of a tree represents a splitting rule for one specific Attribute. 
Only a sub-set of Attributes, specified with the subset ratio criterion, is considered for the splitting rule selection. 
This rule separates values in an optimal way for the selected parameter criterion. 
For classification the rule is separating values belonging to different classes, while for regression it separates them in order to reduce the error made by the estimation. The building of new nodes is repeated until the stopping criteria are met.

Each random tree generates a prediction for each Example by following the branches of the tree in accordance to the splitting rules and evaluating the leaf. Class predictions are based on the majority of Examples, while estimations are obtained through the average of values reaching a leaf. The resulting model is a voting model of all created random trees. Since all single predictions are considered equally important, and are based on sub-sets of Examples the resulting prediction tends to vary less than the single predictions.



- advantages over econometric methods. Random forest have several advantages over econometric models.
  * The great pros of Random Forests are that the effects of  heteroscedasticity, outliers, and other data anomalies are reduced due to the large amount of individual tree learners and majority voting (Breiman, 2011).
  * The  algorithm provides unbiased estimates of model generalization error.
  * Detect nonlinear relationships and good works with the high dimensional datasets (Siroky, 2009). 

- steps that we take.

- results we get..

Moreover, this approach is also used to rank the importance of variables/classifier in regression and classification tasks (variable selection method). 


## my interview writing..




## information drafts below
----------- 




### RF advantages. 

[random forest econometrics advantages](http://qetartu.blogspot.jp/2016/12/applied-econometrics-statistical.html)

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

https://deeplearning4j.org/random-forest.html
Random forests are made of many decision trees. They are ensembles of decision trees, each decision tree created by using a subset of the attributes used to classify a given population (they are sub-trees, see above). Those decision trees vote on how to classify a given instance of input data, and the random forest bootstraps those votes to choose the best prediction. This is done to prevent overfitting, a common flaw of decision trees.

A random forest is a supervised classification algorithm. It creates a forest (many decision trees) and orders their nodes and splits randomly. The more trees in the forest, the better the results it can produce.

If you input a training dataset with targets and features into the decision tree, it will formulate some set of rules that can be used to perform predictions.

Example: You want to predict whether a visitor to your e-commerce Web site will enjoy a mystery novel. First, collect information about past books they’ve read and liked. Metadata about the novels will be the input; e.g. number of pages, author, publication date, which series it’s part of if any. The decision tree contains rules that apply to those features; for example, some readers like very long books and some don’t. Inputting metadata about new novels will result in a prediction regarding whether or not the Web site visitor in question would like that novel. Arranging the nodes and defining the rules relies on information gain and Gini-index calculations. With random forests, finding the root node and splitting the feature nodes is done randomly.


- key words: decision trees, 

1. random forest is a adapation of machine learning algorithm based on machine learning. rf improves overfitting? rf aggregates (bootstrap aggregation), so that the result is more accurate??? rf is exempt from multi-collinearilty and endogneity problems?
1.1
1.2
1.3

### RF brief introductions.



### 
