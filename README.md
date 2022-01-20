# AWESOME-Debias-Recsys [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
Related Papers for bias and debias in machine learning (we mainly focus on its application in recommender systems).

# statement
Since there are tons of new papers on related topic in many conferences, we are only able to update those we just read and consider as insightful and useful.
You are always welcomed to submit a pull request for the related and unlisted papers on debias ML, which are published on peer-review conferences (SIGIR/WWW/AAAI/KDD etc.) or released on arXiv.

## Contents

- <a href="#Survey"> Survey Resources</a><br>
- <a href="#Article">Article Resources</a><br>
- <a href="#Journal">Journal Resources</a><br>
- <a href="#Tutorial">Tutorial Resources</a><br>

|Category|Subtype|Stages in the loop|Cause|Effect|Major Solutions|
|---|---|---|---|---|---|
|**Data Bias**|Selection Bias|Use→Data|users' self-selection|skewed observed rating distribution|Data Imputation;Propensity Score;Joint Generative  Model;Doubly Robust Model|
|**Data Bias**|Exposure Bias|User→️Data|item popularity;intervened by systems;User behavior and background|unobserved  interactions do not mean negative|Giving confidence weights by heuristic, sampling or exposure-based model;Propensity score;Causality-based Model|
|**Data Bias**|Conformity Bias|User→️Data|conformity|skewed interaction labels|Modeling social or popularity effect|
|**Data Bias**|Position Bias|User→️Data|trust top of lists;exposed to top of lists|unreliable positive data|click models;Propensity Score;Trust-aware Model|
|**Model Bias**|Inductive Bias|Data→️Model|researchers  or engineers created|better generalization,lower variance or faster recommendation|-|
|**Bias**|Popularity Bias|Model→️User|Algorithm and unbalanced data|matthew effect|Regularization;Adversarial Learning;Causal graph|
|**Bias**|Unfairness|Model→️User|Algorithm and unbalanced data|unfairness for certain groups|ReBalancing;regularization;Adversarial Learning;Causal Modeling|
|**Bias**|Bias amplification in the loop|All|Feed|Enhance and spread bias|Break the loop by collecting random data or using reinforcement learning|

<a id='Survey'></a>
## Survey
* [Bias and Debias in Recommender System: A Survey and Future Directions](https://arxiv.org/abs/2010.03240) (Arxiv)

<a id='Article'></a>
## Article
* [Should i follow the crowd?: A probabilistic analysis of the effectiveness of popularity in recommender systems](https://dl.acm.org/doi/10.1145/3209978.3210014) (SIGIR2018 Best Paper Award) <br/> Wait for content update...
* [Controlling Fairness and Bias in Dynamic Learning-to-Rank](http://www.cs.cornell.edu/people/tj/publications/morik_etal_20a.pdf) (SIGIR2020 Best Paper Award) <br/> Wait for content update...
* [Computationally Efficient Optimization of Plackett-Luce Ranking Models for Relevance and Fairness](https://arxiv.org/abs/2105.00855) (SIGIR2021 Best Paper Award) <br/> Wait for content update...
* [Causal Intervention for Leveraging Popularity Bias in Recommendation](https://arxiv.org/abs/2105.06067) (SIGIR2021 Best Paper Award) <br/> Wait for content update...
* [Modeling Users’ Exposure with Social KnowledgeInfluence and Consumption Influence for Recommendation](https://dl.acm.org/doi/10.1145/3269206.3271742) (CIKM2018) <br/> Wait for content update...
* [Modeling user exposure in recommendation](https://arxiv.org/abs/1510.07025) (WWW2016) <br/> Wait for content update...

<a id='Tutorial'></a>
## Related tutorials
* [Bias Issues and Solutions in Recommender System: Tutorial on the RecSys 2021]