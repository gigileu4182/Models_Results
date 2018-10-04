# some are in evernote.

## <h3> ------------- Machine learning Concepts</h3>

//Common attributes and methods
- weaker learner, stong learner? 
  - **A weak learner** is defined to be a classifier that is only slightly correlated with the true classification (it can label examples better than random guessing). In contrast, **a strong learner** is a classifier that is arbitrarily well-correlated with the true classification. 

- **stacking** is adding new features. but there is over-identification problem. you are staying just at the algorithm surface, not into the math. 
  - bad example1: [kaggle stacking](http://blog.kaggle.com/2016/12/27/a-kagglers-guide-to-model-stacking-in-practice/)
- Boosting and bagging
  - !! good: [https://quantdare.com/what-is-the-difference-between-bagging-and-boosting/](good example, differences between boosting and bagging)...... boosting is concentrating on the **not well classifiend points**, and giving more weight to the correct **learners (same model but different data inputs)**! 
  - Boosting is tracking the learners. Boosting is sequential. Bagging is bootstraping with replacement, at each step, is parallel


## <h3>---------------- Machine learning methods </h3>

- **naives bayes**, bayes network (under construction! local lyx)
  - terminlogogies.
  - independence assumption? TO REDUCE computational...?
  - EM algorithm..
  - map, Maximum a posteriori estimation estimate (a limit of Bayes estimators". )
  - continous, discrete..
    - continous... **best:: Naive Bayes Classifiers that Perform Well with Continuous Variables**
  

- support vector machine.
  - keywords: kernels (dual problem), soft margin (), regularization (should we strictly classify?), gamma (should we consider all the points?) 
  - resources:
    - kws: support vector machine from scratch --##-- (find the `symbolic` optimization)(http://ecomunsing.com/build-your-own-support-vector-machine)
    - 


- Tree based methods..... 
  - random forest: https://machinelearningmastery.com/implement-random-forest-scratch-python/
  - Xgboost: https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/
  - Decision trees resources.
    - (1)
      * https://www.cs.indiana.edu/~predrag/classes/2018springb565/
      * https://medium.com/mlreview/gradient-boosting-from-scratch-1e317ae4587d

        ```
        come on
        ```


- Adaboost (instance): boosting, convex
- logitboost (instance): boosting, convex
- Brownboost (instance): non-convex
- Catboost
  - differences: https://towardsdatascience.com/catboost-vs-light-gbm-vs-xgboost-5f93620723db
- gradient boost from scratch
  - https://medium.com/mlreview/gradient-boosting-from-scratch-1e317ae4587d


- 4-lectures.. http://www.robots.ox.ac.uk/~az/lectures/ml
- simple explanations. https://medium.com/machine-learning-101/chapter-2-svm-support-vector-machine-theory-f0812effc72

- lasso model from scratch:
  - https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-ridge-lasso-regression-python/

- **deep learning latent variable** (https://ermongroup.github.io/cs228-notes/extras/readings/)
  - this site is very good, because I could also learn how to build websites~~



## Econometrics
- bayesian regression
  * example bayesian regression in r
    - http://www-math.bgsu.edu/~albert/bcwr/
    - http://www.tqmp.org/RegularArticles/vol14-2/p099/p099.pdf

## non linear regression..
- heteroskedasticity econometrics regression in r, http://www.brodrigues.co/blog/2018-07-08-rob_stderr/
- !!! influential points, multicolinearity, weight least squares. 
  - https://onlinecourses.science.psu.edu/stat501/node/352/   (change 501. to 502 etc...... ) (also check the **r software help**)
  - stuctural/data based **multicolinearlity**.
  - how to choose weights? http://www.markirwin.net/stat149/Lecture/Lecture3.pdf 
  - categorical center mean outliers: https://epub.ub.uni-muenchen.de/2081/1/report008_statistics.pdf

## Others..
1. is the loss function unitless..? standadization?
2. interaction
3. multiple index.. [single index model econometrics](https://www.springer.com/cda/content/document/cda_downloaddocument/9780387928692-c1.pdf?SGWID=0-0-45-777205-p173900303)
- Books on machine learning, statistical learning, deep learning, reinforcement learning.
https://github.com/josephmisiti/awesome-machine-learning/blob/master/books.md


## Missing values..
1. Terminlogies
  - Understanding. MCAR, MAR, MNAR. you may wonder why the definitions look so abstract and somehow indistinguishable.. well, because in reality, the sitiation is very complicated, and you do not want to make it wrong. We start with an example.
  
  - Lising deletion. (). pairewise deletion (). (regression) (stochastic) , multiple imputation...
  
