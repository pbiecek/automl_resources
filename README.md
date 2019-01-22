# Interesting resources related to AutoML

## Papers

### 2018

* [Warmstarting of Model-based Algorithm Configuration](https://arxiv.org/abs/1709.04636); Marius Lindauer, Frank Hutter; The performance of many hard combinatorial problem solvers depends strongly on their parameter settings, and since manual parameter tuning is both tedious and suboptimal the AI community has recently developed several algorithm configuration (AC) methods to automatically address this problem. While all existing AC methods start the configuration process of an algorithm A from scratch for each new type of benchmark instances, here we propose to exploit information about A's performance on previous benchmarks in order to warmstart its configuration on new types of benchmarks. We introduce two complementary ways in which we can exploit this information to warmstart AC methods based on a predictive model. Experiments for optimizing a very flexible modern SAT solver on twelve different instance sets show that our methods often yield substantial speedups over existing AC methods (up to 165-fold) and can also find substantially better configurations given the same compute budget.

* [Long-Term Trends in the Public Perception of Artificial Intelligence](https://arxiv.org/abs/1609.04904); Ethan Fast, Eric Horvitz; Analyses of text corpora over time can reveal trends in beliefs, interest, and sentiment about a topic. We focus on views expressed about artificial intelligence (AI) in the New York Times over a 30-year period. General interest, awareness, and discussion about AI has waxed and waned since the field was founded in 1956. We present a set of measures that captures levels of engagement, measures of pessimism and optimism, the prevalence of specific hopes and concerns, and topics that are linked to discussions about AI over decades. We find that discussion of AI has increased sharply since 2009, and that these discussions have been consistently more optimistic than pessimistic. However, when we examine specific concerns, we find that worries of loss of control of AI, ethical concerns for AI, and the negative impact of AI on work have grown in recent years. We also find that hopes for AI in healthcare and education have increased over time.

* [Relational Learning and Feature Extraction by Querying over Heterogeneous Information Networks](https://arxiv.org/abs/1707.07794); Parisa Kordjamshidi, Sameer Singh, Daniel Khashabi, Christos Christodoulopoulos, Mark Summons, Saurabh Sinha, Dan Roth; Many real world systems need to operate on heterogeneous information networks that consist of numerous interacting components of different types. Examples include systems that perform data analysis on biological information networks; social networks; and information extraction systems processing unstructured data to convert raw text to knowledge graphs. Many previous works describe specialized approaches to perform specific types of analysis, mining and learning on such networks. In this work, we propose a unified framework consisting of a data model -a graph with a first order schema along with a declarative language for constructing, querying and manipulating such networks in ways that facilitate relational and structured machine learning. In particular, we provide an initial prototype for a relational and graph traversal query language where queries are directly used as relational features for structured machine learning models. Feature extraction is performed by making declarative graph traversal queries. Learning and inference models can directly operate on this relational representation and augment it with new data and knowledge that, in turn, is integrated seamlessly into the relational structure to support new predictions. We demonstrate this system's capabilities by showcasing tasks in natural language processing and computational biology domains.

* [Approximation Trees: Statistical Stability in Model Distillation](https://arxiv.org/abs/1808.07573); Yichen Zhou, Zhengze Zhou, Giles Hooker; This paper examines the stability of learned explanations for black-box predictions via model distillation with decision trees. One approach to intelligibility in machine learning is to use an understandable student model to mimic the output of an accurate teacher. Here, we consider the use of regression trees as a student model, in which nodes of the tree can be used as explanations for particular predictions, and the whole structure of the tree can be used as a global representation of the resulting function. However, individual trees are sensitive to the particular data sets used to train them, and an interpretation of a student model may be suspect if small changes in the training data have a large effect on it. In this context, access to outcomes from a teacher helps to stabilize the greedy splitting strategy by generating a much larger corpus of training examples than was originally available. We develop tests to ensure that enough examples are generated at each split so that the same splitting rule would be chosen with high probability were the tree to be re trained. Further, we develop a stopping rule to indicate how deep the tree should be built based on recent results on the variability of Random Forests when these are used as the teacher. We provide concrete examples of these procedures on the CAD-MDD and COMPAS data sets.

### 2017

* [vtreat: a data.frame Processor for Predictive Modeling](https://arxiv.org/pdf/1611.09477.pdf); Nina Zumel, John Mount; vtreat prepares real-world data for predictive modeling in a reproducible and statistically sound manner, and is a valuable addition to the data science work-flow. Missing or invalid values are replaced with safe valid values, and further indicated by additional dummy variables. Categorical variables are represented in a manner that is robust to the appearance of novel levels during model application. Estimated variable significances are supplied for user-controlled variable pruning.

### 2016

* [A brief Review of the ChaLearn AutoML Challenge](https://docs.google.com/a/chalearn.org/viewer?a=v&pid=sites&srcid=Y2hhbGVhcm4ub3JnfGF1dG9tbHxneDoyYThjZjhhNzRjMzI3MTg4); Isabelle Guyon et al; The ChaLearn AutoML Challenge team conducted a large scale evaluation of fully automatic, black-box learning machines for feature-based classification and regression problems. The test bed was composed of 30 data sets from a wide variety of application domains and ranged across different types of complexity. Over six rounds, participants succeeded in delivering AutoML software capable of being trained and tested without human intervention. Although improvements can still be made to close the gap between human-tweaked and AutoML models, this competition contributes to the development of fully automated environments by challenging practitioners to solve problems under specific constraints and sharing their approaches; the platform will remain available for post-challenge submissions at http://codalab.org/AutoML.

* [Entity Embeddings of Categorical Variables](https://arxiv.org/pdf/1604.06737.pdf); Cheng Guo and Felix Berkhahn; We map categorical variables in a function approximation problem into Euclidean spaces, which are the entity embeddings of the categorical variables. ... As entity embedding defines a distance measure for categorical variables it can be used for visualizing categorical data and for data clustering.

### 2013

* [An Evaluation of Sequential Model-Based Optimization for Expensive Blackbox Functions](http://aad.informatik.uni-freiburg.de/papers/13-GECCO-BBOB_SMAC.pdf); Frank Hutter, Holger Hoos, Kevin Leyton-Brown; We benchmark a sequential model-based optimization procedure, SMAC-BBOB, on the BBOB set of blackbox functions. We demonstrate that with a small budget of 10×D evaluations of D-dimensional functions, SMAC-BBOB in most cases outperforms the state-ofthe-art blackbox optimizer CMA-ES. However, CMA-ES benefits more from growing the budget to 100× D, and for larger number of function evaluations SMAC-BBOB also requires increasingly large computational resources for building and using its models.

### 2008 

* [Isolation Forest](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf); Fei Tony Liu, Kai Ming Ting, Zhi-Hua Zhou; Most existing model-based approaches to anomaly detection construct a profile of normal instances, then identify instances that do not conform to the normal profile as anomalies. This paper proposes a fundamentally different model-based method that explicitly isolates anomalies instead of profiles normal points. Our empirical evaluation shows that iForest performs favourably to ORCA, a near-linear time complexity distance-based method, LOF and Random Forests in terms of AUC and processing time, and especially in large data sets. iForest also works well in high dimensional problems which have a large number of irrelevant attributes, and in situations where training set does not contain any anomalies.

## Books

### 2018

* [AUTOML: METHODS, SYSTEMS, CHALLENGES](https://www.automl.org/book/)

## Workshop

### 2018

* [www.automl.org](https://www.automl.org/events/); https://www.automl.org/

## Tools

### 2018

* [DEvol - Deep Neural Network Evolution](https://github.com/joeddav/devol); 

* [MLFlow](https://github.com/mlflow/mlflow/tree/master/mlflow/R/mlflow); MLflow Tracking allows you to logging parameters, code versions, metrics, and output files when running R code and for later visualizing the results. MLflow allows you to group runs under experiments, which can be useful for comparing runs intended to tackle a particular task. You can create and activate a new experiment locally using mlflow as follows:

* [splinetree: Longitudinal Regression Trees and Forests](https://cran.r-project.org/web/packages/splinetree/index.html); Anna Neufeld, Brianna Heggeseth; Builds regression trees and random forests for longitudinal or functional data using a spline projection method. Implements and extends the work of Yu and Lambert (1999). This method allows trees and forests to be built while considering either level and shape or only shape of response trajectories.

* [embed: Extra Recipes for Encoding Categorical Predictors](https://cran.r-project.org/web/packages/embed/index.html); 	Max Kuhn; Factor predictors can be converted to one or more numeric representations using simple generalized linear models <arXiv:1611.09477> or nonlinear models <arXiv:1604.06737>. All encoding methods are supervised.

### 2017

* [Michelangelo](https://eng.uber.com/michelangelo/); Uber Engineering is committed to developing technologies that create seamless, impactful experiences for our customers. We are increasingly investing in artificial intelligence (AI) and machine learning (ML) to fulfill this vision. At Uber, our contribution to this space is Michelangelo, an internal ML-as-a-service platform that democratizes machine learning and makes scaling AI to meet the needs of business as easy as requesting a ride.

## Articles

### 2018

* [What’s New in Deep Learning Research: OpenAI and DeepMind Join Forces to Achieve Superhuman Performance in Reinforcement Learning](https://towardsdatascience.com/whats-new-in-deep-learning-research-openai-and-deepmind-join-forces-to-achieve-superhuman-48e7d1accf85); DeepMind and OpenAI are two artificial intelligence(AI) companies at the center of advancements in reinforcement learning(RL). From AlphaGo to Dota2 Five, both DeepMind and OpenAI have been pushing the boundaries of RL applications to surpass human in complex cognitive tasks. Last week, the two research powerhouses decided to team up in a new paper that proposes a new method to train RL agents in ways that enables them to achieve superhuman performance.

* [Auto is the new black — Google AutoML, Microsoft Automated ML, AutoKeras and auto-sklearn](https://medium.com/@santiagof/auto-is-the-new-black-google-automl-microsoft-automated-ml-autokeras-and-auto-sklearn-80d1d3c3005c); Motivation: Life is hard. Achieving state-of-the-art performance in a given data set is hard. It usually implies carefully selecting the right data pre-prossessing tasks, picking the right algorithm, model and architecture and pairing it with the right set of parameters. This end-to-end process is usually called Machine Learning Pipeline. There is no rule of thumb in which direction to go and, with more models beings developed all the time, even picking the right model is becoming challenging. Hyper-parameter tuning usually requires walking or sampling over all the possible values and just trying them out. However, there is no any warranty about finding something useful. In this context, automating the selection and tuning of machine learning pipelines has long been one of the goals of the machine learning community. This kind of task are usually referred as meta-learning — learning about learning.
