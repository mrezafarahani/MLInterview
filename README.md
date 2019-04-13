# ML/DS Interview Guide
A Cheatsheet to prepare for ML/Data Science interviews, at each section, I listed the topics you need to cover and a link to a source which goes over the topic comprehensively.

When I started preparing this document It was just a checklist for myself but after my mentorship experience, I noticed the structure of such a document helps people to organize their minds. 

During the past 4 years I had the chance to interview many data scientists and get interviewed by both established companies and startups. I am planning to write more about those experiences.

I used [hired](https://hired.com/x/618y6) during last 3 months to get a couple of interviews, the job I landed at the end was not linked to [hired](https://hired.com/x/618y6), however, those interviews helped me to refine my knowledge and subsequently this document<sup>[1](#myfootnote1)</sup>.


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
	* 5.1. [Two-Class Classification](#Two-ClassClassification)
	* 5.2. [Multiclass Classification](#MulticlassClassification)
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

:tv: Head over to [Khan Academy](https://www.khanacademy.org/math/ap-statistics/tests-significance-ap) for the review.

:clock1030: Estimated Review Time 4 hours

##  2. <a name='LinearAlgebraoptional'></a>Linear Algebra (optional)
This section is needed the most for positions related to NLP, Recommender Engines and Advanced Machine Learning.
* Eigenvalues and Eigenvectors
* Kernel, Range, Nullity, Rank
* Singular Value Decomposition
* Matrix Factorization

To learn about this topic check [Linear Algebra by Cherney et. al.](https://www.math.ucdavis.edu/~linear/linear-guest.pdf) or [khan academy website](https://www.khanacademy.org/math/linear-algebra).
##  3. <a name='DataPreparation'></a>Data Preparation
###  3.1. <a name='FeatureEngineering'></a>Feature Engineering
* typical groupby-agg,
* counting,
* [categorical encoding](https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159) (Ordinal, OneHot, Binary, BaseN, Hashing),
* count vector,
* FM/FFM,
* NN and
* out of fold model
###  3.2. <a name='FeatureSelection'></a>Feature Selection
* All Subsets
* Filter Methods -- Chi squared test, information gain and correlation coefficient scores
* Wrapper Methods -- Stepwise Procedures (backward and forward)
* Embedded Methods -- LASSO, Elastic Net and Ridge Regression

Here is a good easy read from [DataCamp](https://www.datacamp.com/community/tutorials/feature-selection-python)


* Note that PCA is a dimensionality reduction method and not a feature selection method.
[This datacamp link has whatever you need to know](https://www.datacamp.com/community/tutorials/feature-selection-python)
##  4. <a name='Algorithms'></a>Algorithms
###  4.1. <a name='Classification'></a>Classification
* Logistic Regression
* K-Nearest Neighbor
* Decision Tree
* Ensemble Methods -- Random Forest, Gradient Boosting Machines, XGBoost

###  4.2. <a name='Clustering'></a>Clustering
####  4.2.1. <a name='HardClustering'></a>Hard Clustering
* K-means Clustering
* Hierarchical Clustering
####  4.2.2. <a name='SoftClustering'></a>Soft Clustering
* C-means Clustering
* GMM

###  4.3. <a name='Regression'></a>Regression
* Linear Regression 
* Non-linear Regression

##  5. <a name='ModelEvaluationModelSelection'></a>Model Evaluation, Model Selection

###  5.1. <a name='Two-ClassClassification'></a>Two-Class Classification
###  5.2. <a name='MulticlassClassification'></a>Multiclass Classification
###  5.3. <a name='Regression-1'></a>Regression
Most of this section is taken from [this paper](https://arxiv.org/pdf/1811.12808.pdf)

##  6. <a name='Coding'></a>Coding
###  6.1. <a name='SQL'></a>SQL
SQL is the main language used in enterprise while dealing with data and databses. You need to know basics of SQL coding. There are a lot of SQL flavours, however, you are not required to know them all. These are the fields I recommend to learn:

* Data Manipulation
* Queries 
* Joins (Multitables)
* Aggregate functions

To learn more just take this [7-Hour course from codeacademy](https://www.codecademy.com/learn/learn-sql).
###  6.2. <a name='PythonBasics'></a>Python Basics
* Data Manipulation (Numpy and Pandas)
* Machine Learning (Sci-kit Learn)
* Visualization (MatplotLib, Seaborn)
* Advance Machine Learning (TensorFlow)

###  6.3. <a name='DataStructureandAlgorithms'></a>Data Structure and Algorithms


<a name="myfootnote1">1</a>: The hired link is a referral link which helps me to continue writing in this topic.

