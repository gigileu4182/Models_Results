## 原则

问题?和**预期**不符，outliers?
- weak correlation, why? 度degree，质quality

- 单变量 - (异质性 degree of heterogeneity) 
  == **conditional** quantile.. heterogeneity
  == distribution (3 moments), why so intensive? why different?

- 多变量 - the type of relation? for each type of relation, its degree? heterogeneity?
  - conditional relationship
  - correlations

捉关键term，关系，顺序。

**共性**。

reference 即 given？每个instance，所属的class里都有attributes and methods. these attributes and methods are correlated with those attributes and methods in other classes. 这些共性有多有少，有强有弱。
                一个CLASS里的每个instance，其实也是唯一的。对于他们来说，他们被放到这个class里，因为我们关注的需要（russell）。那么每个instance其实是有唯一的attributes和methods的列表的。
                fixed effect背后的原因？
                计量模型就是找共性，给出了一定的attributes（不要太多也不要太少的情况下）招共性。太多了多的话，个性太明显？因为样本就缩到很小了！
                那么多于股票来说，就是找他们的共振属性，排序（我只需要离散），再配合基本面来选择网格买点！



# Models_Results


- random coefficient ... 
  - interaction == coefficient depends upon other variables == heterogeneity.
  - 

## 计量，统计，my modelling thought:

0. 
1. discrete/continuous
2. there is always a trade-off.
3. one variable, 2-... more... conditional
4. non-para needs big observations, 
  - but can be used to obtain local problems.
  - many small bumps (non-smoothness) imply big data problems
  - uniform h : two ways of being selected. cross validation... 
  - local linear.. local constant...
  - can not predict at places where there is no data.
  - smooth coefficient (in particular becomes model with interaction terms), different from random coeffcient (the parameter change comes from randomness)
5. sample selection?
6. outliers? matching, discrete/continuous

statistical modelling mood..
constrained regression..


模型2：
为什么有时会空白？没有预期，调出模型。
场景（）

#### 新的计量模型探索：
- quantile regression
- interval regression
- (symbolic data analysis) Constrained linear regression models for symbolic interval-valued variables 
- hmm

#### others

* econometrics assumptions of the independent variables
  * https://www.albert.io/blog/key-assumptions-of-ols-econometrics-review/
* control variable econometrics
  * control the effect from other than the main variable.
    * https://www.quora.com/What-are-control-variables-and-how-do-I-use-them-in-regression-analysis
  * so we put it there, and if its coefficient be significant, then it is legitimate? because otherwise the assumptions on epsilon (random sampling of individuals/instances) will be incorrect. (female-male height example)
  
