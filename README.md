# Interesting resources related to AutoML

## Papers

### 2018

* [Long-Term Trends in the Public Perception of Artificial Intelligence](https://arxiv.org/abs/1609.04904); Ethan Fast, Eric Horvitz; Analyses of text corpora over time can reveal trends in beliefs, interest, and sentiment about a topic. We focus on views expressed about artificial intelligence (AI) in the New York Times over a 30-year period. General interest, awareness, and discussion about AI has waxed and waned since the field was founded in 1956. We present a set of measures that captures levels of engagement, measures of pessimism and optimism, the prevalence of specific hopes and concerns, and topics that are linked to discussions about AI over decades. We find that discussion of AI has increased sharply since 2009, and that these discussions have been consistently more optimistic than pessimistic. However, when we examine specific concerns, we find that worries of loss of control of AI, ethical concerns for AI, and the negative impact of AI on work have grown in recent years. We also find that hopes for AI in healthcare and education have increased over time.

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

* [What’s New in Deep Learning Research: OpenAI and DeepMind Join Forces to Achieve Superhuman Performance in Reinforcement Learning](https://towardsdatascience.com/whats-new-in-deep-learning-research-openai-and-deepmind-join-forces-to-achieve-superhuman-48e7d1accf85); DeepMind and OpenAI are two artificial intelligence(AI) companies at the center of advancements in reinforcement learning(RL). From AlphaGo to Dota2 Five, both DeepMind and OpenAI have been pushing the boundaries of RL applications to surpass human in complex cognitive tasks. Last week, the two research powerhouses decided to team up in a new paper that proposes a new method to train RL agents in ways that enables them to achieve superhuman performance.

* [Auto is the new black — Google AutoML, Microsoft Automated ML, AutoKeras and auto-sklearn](https://medium.com/@santiagof/auto-is-the-new-black-google-automl-microsoft-automated-ml-autokeras-and-auto-sklearn-80d1d3c3005c); Motivation: Life is hard. Achieving state-of-the-art performance in a given data set is hard. It usually implies carefully selecting the right data pre-prossessing tasks, picking the right algorithm, model and architecture and pairing it with the right set of parameters. This end-to-end process is usually called Machine Learning Pipeline. There is no rule of thumb in which direction to go and, with more models beings developed all the time, even picking the right model is becoming challenging. Hyper-parameter tuning usually requires walking or sampling over all the possible values and just trying them out. However, there is no any warranty about finding something useful. In this context, automating the selection and tuning of machine learning pipelines has long been one of the goals of the machine learning community. This kind of task are usually referred as meta-learning — learning about learning.
