# ML/DS Interview Guide
A Cheatsheet to prepare for ML/Data Science interviews, at each section I listed the topics you need to cover and a link to a source which oes over the topic comprehensively.


## Statistics
* Central Limit Theorem
* Bayes' theorem
* Hopothesis testing
* p-value
## Linear Algebra (optional)
This section is needed the most for positions related to NLP, Recommender Engines and Advanced Machine Learning.
* Eigenvalues and Eigenvectors
* Kernel, Range, Nullity, Rank
* Singular Value Decomposition
* Matrix Factorization

To learn about this topic check [Linear Algebra by Cherney et. al.](https://www.math.ucdavis.edu/~linear/linear-guest.pdf) or [khan academy website](https://www.khanacademy.org/math/linear-algebra).
## Data Preparation
### Feature Engineering
* typical groupby-agg,
* counting,
* [categorical encoding](https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159) (Ordinal, OneHot, Binary, BaseN, Hashing),
* count vector,
* FM/FFM,
* NN and
* out of fold model
### Feature Selection
* All Subsets
* Filter Methods -- Chi squared test, information gain and correlation coefficient scores
* Wrapper Methods -- Stepwise Procedures (backward and forward)
* Embedded Methods -- LASSO, Elastic Net and Ridge Regression

Here is a good easy read from [DataCamp](https://www.datacamp.com/community/tutorials/feature-selection-python)


* Note that PCA is a dimensionality reduction method and not a feature selection method.
[This datacamp link has whatever you need to know](https://www.datacamp.com/community/tutorials/feature-selection-python)
## Algorithms
### Classification
* Logistic Regression
* K-Nearest Neighbor
* Decision Tree
* Ensemble Methods -- Random Forest, Gradient Boosting Machines, XGBoost

### Clustering
#### Hard Clustering
* K-means Clustering
* Hierarchical Clustering
#### Soft Clustering
* C-means Clustering
* GMM

### Regression
* Linear Regression 
* Non-linear Regression

## Model Evaluation, Model Selection

### Two-Class Classification
### Multiclass Classification
### Regression
Most of this section is taken from [this paper](https://arxiv.org/pdf/1811.12808.pdf)

## Coding
### SQL
SQL is the main language used in enterprise while dealing with data and databses. You need to know basics of SQL coding. There are a lot of SQL flavours, however, you are not required to know them all. These are the fields I recommend to learn:

* Data Manipulation
* Queries 
* Joins (Multitables)
* Aggregate functions

To learn more just take this [7-Hour course from codeacademy](https://www.codecademy.com/learn/learn-sql).
### Python Basics
* Data Manipulation (Numpy and Pandas)
* Machine Learning (Sci-kit Learn)
* Visualization (MatplotLib, Seaborn)
* Advance Machine Learning (TensorFlow)

### Data Structure and Algorithms

