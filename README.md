# AWESOME-Multimodal-Retrieval-and-Recommendation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a repository for organizing articles about Retrieval and Recommendation with Multimodal Large Language Models, Large Language Models, and Diffusion Models; Most papers are linked to **my reading notes**. Feel free to visit my [personal homepage](https://shawnchenn.github.io/) and contact me for collaboration and discussion.


### About Me :
I'm a third-year Ph.D. student at the Hong Kong Polytechnic Univerisy, advised by Prof. [Qing Li].


###  🔥 Updated 2024-12-11
- The structure of this repository is being updated.

# Table of Contents (ongoing)
- [Awesome-LLM-Rec](#llm-retrieval-rec)
- [Awesome-MLLM-Rec](#mllm-retrieval-rec)
- [Efficient LLM/MLLM](#efficient-llm-mllm)
- [LLM/MLLM Alignment](#alignment-llm-mllm)
- [Bias in Recommendation](#bias-in-recommendation)

# LLM-based Retrieval or Recommendation
1. (NeurIPS'24) [G-Retriever: Retrieval-Augmented Generation for Textual Graph Understanding and Question Answering](https://openreview.net/forum?id=MPJ3oXtTZl)


# MLLM-based Retrieval or Recommendation


# Efficient LLM MLLM
1. (WWW'24) [Large Multimodal Model Compression via Iterative Efficient Pruning and Distillation](https://zhuanlan.zhihu.com/p/720542712)(address multi-level redundancy via multi-stage pruning and an advanced distillation loss design.)

2.


# Survey and Outlook
1. [万字长文总结多模态大模型最新进展（Modality Bridging篇）](https://zhuanlan.zhihu.com/p/688215018)
2. [万字长文总结多模态大模型最新进展（Video篇）](https://zhuanlan.zhihu.com/p/704246896)
3. [Aligning Large Language Models with Human](https://zhuanlan.zhihu.com/p/693160839)
4. [Bias and Debias in Recommender System: A Survey and Future Directions](https://arxiv.org/abs/2010.03240) 

# Bias in Recommendation

|Category|Subtype|Stages in the loop|Cause|Effect|Major Solutions|
|---|---|---|---|---|---|
|**Data Bias**|<a href="#SB">Selection Bias</a>|Use→Data|users' self-selection|skewed observed rating distribution|Data Imputation;Propensity Score;Joint Generative  Model;Doubly Robust Model|
|**Data Bias**|<a href="#EB">Exposure  Bias</a>|User→️Data|item popularity;intervened by systems;User behavior and background|unobserved  interactions do not mean negative|Giving confidence weights by heuristic, sampling or exposure-based model;Propensity score;Causality-based Model|
|**Data Bias**|Conformity Bias|User→️Data|conformity|skewed interaction labels|Modeling social or popularity effect|
|**Data Bias**|Position Bias|User→️Data|trust top of lists;exposed to top of lists|unreliable positive data|click models;Propensity Score;Trust-aware Model|
|**Model Bias**|Inductive Bias|Data→️Model|researchers  or engineers created|better generalization,lower variance or faster recommendation|-|
|**Result Bias**|Popularity Bias|Model→️User|Algorithm and unbalanced data|matthew effect|Regularization;Adversarial Learning;Causal graph|
|**Result Bias**|Unfairness|Model→️User|Algorithm and unbalanced data|unfairness for certain groups|ReBalancing;regularization;Adversarial Learning;Causal Modeling|
|**Loop Bias**|Bias amplification in the loop|All|Feed|Enhance and spread bias|Break the loop by collecting random data or using reinforcement learning|

* [Fair Sequential Recommendation without User Demographics](https://dl.acm.org/doi/pdf/10.1145/3626772.3657703) (SIGIR 2024)
* [Adaptive Fair Representation Learning for Personalized Fairness in Recommendations via Information Alignment](https://arxiv.org/abs/2404.07494) (SIGIR 2024)
* [Hypergraph Convolutional Network for User-Oriented Fairness in Recommender Systems] (SIGIR 2024)
* [Fair Recommendations with Limited Sensitive Attributes: A Distributionally Robust Optimization Approach] (SIGIR 2024)
* [Can We Trust Recommender System Fairness Evaluation? The Role of Fairness and Relevance] (SIGIR 2024)
* [Language Fairness in Multilingual Information Retrieval] (SIGIR 2024)
* [AIM: Attributing, Interpreting, Mitigating Data Unfairness
] (KDD 2024) 
* [Using Self-supervised Learning Can Improve Model Fairness
] (KDD 2024)
* [Neural Collapse Inspired Debiased Representation Learning for Min-max Fairness] (KDD 2024)
* [Should i follow the crowd?: A probabilistic analysis of the effectiveness of popularity in recommender systems](https://dl.acm.org/doi/10.1145/3209978.3210014) (SIGIR2018 Best Paper Award) <br/> Wait for content update...
* [Controlling Fairness and Bias in Dynamic Learning-to-Rank](http://www.cs.cornell.edu/people/tj/publications/morik_etal_20a.pdf) (SIGIR2020 Best Paper Award) <br/> Wait for content update...
* [Computationally Efficient Optimization of Plackett-Luce Ranking Models for Relevance and Fairness](https://arxiv.org/abs/2105.00855) (SIGIR2021 Best Paper Award) <br/> Wait for content update...
* [Causal Intervention for Leveraging Popularity Bias in Recommendation](https://arxiv.org/abs/2105.06067) (SIGIR2021 Best Paper Award) <br/> Wait for content update...
* [Modeling Users’ Exposure with Social KnowledgeInfluence and Consumption Influence for Recommendation](https://dl.acm.org/doi/10.1145/3269206.3271742) (CIKM2018) 
* [Modeling user exposure in recommendation](https://arxiv.org/abs/1510.07025) (WWW2016) 
