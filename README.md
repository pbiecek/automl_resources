# Interesting resources related to AutoML

## Papers

### 2017

* [vtreat: a data.frame Processor for Predictive Modeling](https://arxiv.org/pdf/1611.09477.pdf); Nina Zumel, John Mount; vtreat prepares real-world data for predictive modeling in a reproducible and statistically sound manner, and is a valuable addition to the data science work-flow. Missing or invalid values are replaced with safe valid values, and further indicated by additional dummy variables. Categorical variables are represented in a manner that is robust to the appearance of novel levels during model application. Estimated variable significances are supplied for user-controlled variable pruning.

### 2016

* [Entity Embeddings of Categorical Variables](https://arxiv.org/pdf/1604.06737.pdf); Cheng Guo and Felix Berkhahn; We map categorical variables in a function approximation problem into Euclidean spaces, which are the entity embeddings of the categorical variables. ... As entity embedding defines a distance measure for categorical variables it can be used for visualizing categorical data and for data clustering.

### 2008 

* [Isolation Forest](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf); Fei Tony Liu, Kai Ming Ting, Zhi-Hua Zhou; Most existing model-based approaches to anomaly detection construct a profile of normal instances, then identify instances that do not conform to the normal profile as anomalies. This paper proposes a fundamentally different model-based method that explicitly isolates anomalies instead of profiles normal points. Our empirical evaluation shows that iForest performs favourably to ORCA, a near-linear time complexity distance-based method, LOF and Random Forests in terms of AUC and processing time, and especially in large data sets. iForest also works well in high dimensional problems which have a large number of irrelevant attributes, and in situations where training set does not contain any anomalies.

## Books



## Tools

### 2018

* [splinetree: Longitudinal Regression Trees and Forests](https://cran.r-project.org/web/packages/splinetree/index.html); Anna Neufeld, Brianna Heggeseth; Builds regression trees and random forests for longitudinal or functional data using a spline projection method. Implements and extends the work of Yu and Lambert (1999). This method allows trees and forests to be built while considering either level and shape or only shape of response trajectories.

* [embed: Extra Recipes for Encoding Categorical Predictors](https://cran.r-project.org/web/packages/embed/index.html); 	Max Kuhn; Factor predictors can be converted to one or more numeric representations using simple generalized linear models <arXiv:1611.09477> or nonlinear models <arXiv:1604.06737>. All encoding methods are supervised.

## Articles

### 2018

* [Auto is the new black — Google AutoML, Microsoft Automated ML, AutoKeras and auto-sklearn](https://medium.com/@santiagof/auto-is-the-new-black-google-automl-microsoft-automated-ml-autokeras-and-auto-sklearn-80d1d3c3005c); Motivation: Life is hard. Achieving state-of-the-art performance in a given data set is hard. It usually implies carefully selecting the right data pre-prossessing tasks, picking the right algorithm, model and architecture and pairing it with the right set of parameters. This end-to-end process is usually called Machine Learning Pipeline. There is no rule of thumb in which direction to go and, with more models beings developed all the time, even picking the right model is becoming challenging. Hyper-parameter tuning usually requires walking or sampling over all the possible values and just trying them out. However, there is no any warranty about finding something useful. In this context, automating the selection and tuning of machine learning pipelines has long been one of the goals of the machine learning community. This kind of task are usually referred as meta-learning — learning about learning.
