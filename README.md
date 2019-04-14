# Data Science Interview Guide
A Cheatsheet to prepare for Data Science interviews, at each section, I listed the topics you need to cover and a link to a source which goes over the topic comprehensively.

When I started preparing this document It was just a checklist for myself but after my mentorship experience, I noticed the structure of such a document helps people to organize their minds. 

During the past 4 years, I had the chance to interview many data scientists and get interviewed by both established companies and startups. I am planning to write more about those experiences.

I used :rocket: [hired](https://hired.com/x/618y6) during last 3 months to get a couple of interviews, the job I landed at the end was not linked to :rocket: [hired](https://hired.com/x/618y6), however, those interviews helped me to refine my knowledge and subsequently this document<sup>[1](#myfootnote1)</sup>.


<!-- vscode-markdown-toc -->
1. [Statistics](#Statistics)
2. [Linear Algebra (optional)](#LinearAlgebraoptional)
3. [Data Preparation](#DataPreparation)
	* 3.1. [Feature Engineering](#FeatureEngineering)
	* 3.2. [Feature Selection](#FeatureSelection)
4. [Algorithms](#Algorithms)
	* 4.1. [Classification](#Classification)
	* 4.2. [Clustering](#Clustering)
		* 4.2.1. [Hard Clustering](#HardClustering)
		* 4.2.2. [Soft Clustering](#SoftClustering)
	* 4.3. [Regression](#Regression)
5. [Model Evaluation, Model Selection](#ModelEvaluationModelSelection)
	* 5.1. [Model Errors](#Model-Errors)
	* 5.2. [Classification](#Classification)
	* 5.3. [Regression](#Regression-1)
6. [Coding](#Coding)
	* 6.1. [SQL](#SQL)
	* 6.2. [Python Basics](#PythonBasics)
	* 6.3. [Data Structure and Algorithms](#DataStructureandAlgorithms)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Statistics'></a>Statistics
* Central Limit Theorem
* Bayes' theorem
* Hopothesis testing
* p-value

:tv: Head over to [Khan Academy](https://www.khanacademy.org/math/ap-statistics/tests-significance-ap) for the review lesson.

:clock1030: Estimated Review Time 3 hours

##  2. <a name='LinearAlgebraoptional'></a>Linear Algebra (optional)
This section is needed the most for positions related to NLP, Recommender Engines and Advanced Machine Learning.
* Eigenvalues and Eigenvectors
* Kernel, Range, Nullity, Rank
* Singular Value Decomposition
* Matrix Factorization

:tv: To learn about this topic check [khan academy website](https://www.khanacademy.org/math/linear-algebra).

:clock1030: Estimated Review Time 3 hours

:eyeglasses: Extra Resources: [Linear Algebra by Cherney et. al.](https://www.math.ucdavis.edu/~linear/linear-guest.pdf)

##  3. <a name='DataPreparation'></a>Data Preparation
###  3.1. <a name='FeatureEngineering'></a>Feature Engineering
* [Grouping and Aggregation](https://towardsdatascience.com/aggregation-and-grouping-66396f26dd95) (Counting, Mean, Median, STD, Max, Min, ...),
* [Categorical Encoding](https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159) (Ordinal, OneHot, Binary, BaseN, Hashing),
* Feature Transformation,
* Deep Learning methods, e.g., Autoencoding (optional)

:book: I am looking for something more comprehensive for this section but [this article](https://towardsdatascience.com/feature-engineering-what-powers-machine-learning-93ab191bcc2d) is still a good read.


###  3.2. <a name='FeatureSelection'></a>Feature Selection
* All Subsets
* Filter Methods -- Chi squared test, information gain and correlation coefficient scores
* Wrapper Methods -- Stepwise Procedures (backward and forward)
* Embedded Methods -- LASSO, Elastic Net and Ridge Regression

:computer: Here is a good easy read from [DataCamp](https://www.datacamp.com/community/tutorials/feature-selection-python).

:clock1030: Estimated Review Time 3 hours

:grey_exclamation: Note that PCA is a feature engineering and/or dimentionality reduction method and not a feature selection method.
[This datacamp article](https://www.datacamp.com/community/tutorials/feature-selection-python) has whatever you need to know.
##  4. <a name='Algorithms'></a>Algorithms
###  4.1. <a name='Classification'></a>Classification
* Logistic Regression
* K-Nearest Neighbor
* Decision Tree
* Ensemble Methods -- Random Forest, Gradient Boosting Machines, XGBoost

:tv: Take a look at [this video](https://www.coursera.org/lecture/machine-learning/classification-wlPeP) by Andrew Ng for Logistic Regression.

:book: For Decision Tree topic take a look at [this medium post](https://medium.com/deep-math-machine-learning-ai/chapter-4-decision-trees-algorithms-b93975f7a1f1).

###  4.2. <a name='Clustering'></a>Clustering
####  4.2.1. <a name='HardClustering'></a>Hard Clustering
* [K-means Clustering](https://www.datascience.com/blog/k-means-clustering)
* [Hierarchical Clustering](https://towardsdatascience.com/understanding-the-concept-of-hierarchical-clustering-technique-c6e8243758ec)

####  4.2.2. <a name='SoftClustering'></a>Soft Clustering
* [Fuzzy clustering](https://en.wikipedia.org/wiki/Fuzzy_clustering)
* [Gaussian mixture models](https://scikit-learn.org/stable/modules/mixture.html)

###  4.3. <a name='Regression'></a>Regression
* Linear Regression 
* Non-linear Regression

:tv: This a great overview of [regression in Khan Academy](https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data#more-on-regression). 

:clock1030: Estimated Review Time 5 hours

##  5. <a name='ModelEvaluationModelSelection'></a>Model Evaluation, Model Selection

###  5.1. <a name='Model-Errors'></a>Model Errors
* Bias and Variance
* Relation of Overfitting to bias and vairance
* Cross Validation

:book: Most of this section is taken from [this paper](https://arxiv.org/pdf/1811.12808.pdf)

###  5.2. <a name='Classification'></a>Classification
* Accuracy
* Log-loss
* Percision-Recall (Confusion Metrics)
* F1-Score
* ROC-AUC

:book: [This article](https://medium.com/usf-msds/choosing-the-right-metric-for-evaluating-machine-learning-models-part-2-86d5649a5428) goes over most these methods.

###  5.3. <a name='Regression-1'></a>Regression
* Mean Squar Error (MSE) & Mean Squar Error
* R-Square
* Mean Absolute Percentage Error (MAPE)

:tv: For the regression model evaluation take a look at the [Khan Academy course](https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data#more-on-regression) on regression.

:clock1030: Estimated Review Time 3 hours

##  6. <a name='Coding'></a>Coding
###  6.1. <a name='SQL'></a>SQL
SQL is the main language used across enterprises while dealing with data and databases. You need to know the basics of SQL coding. There are a lot of SQL flavours, however, you are not required to know them all. These are the fields I recommend to learn:

* Data Manipulation
* Queries 
* Joins (Multitables)
* Aggregate functions

:computer: To learn more just take this [7-Hour course from codeacademy](https://www.codecademy.com/learn/learn-sql).


###  6.2. <a name='PythonBasics'></a>Python Basics
* Data Manipulation (Numpy and Pandas)
* Machine Learning (Sci-kit Learn)
* Visualization (MatplotLib, Seaborn)
* Advance Machine Learning (TensorFlow)

:computer: To learn more just take this [7-Hour course from DataCamp](https://www.datacamp.com/courses/intro-to-python-for-data-science). 


###  6.3. <a name='DataStructureandAlgorithms'></a>Data Structure and Algorithms
* Arrays
* Linked Lists
* Dictionary (Hash Function)
* Trees
* Algorithm Complexity (Big-O notion)

:computer: head over to [DataCamp](https://www.datacamp.com/community/tutorials/data-structures-python) to learn more about data structures in python.

:clock1030: Estimated Review Time 5 hours (Assuming you may skip some parts)


------
<a name="myfootnote1">1</a>: The hired link is a referral link which helps me to continue writing in this topic.

