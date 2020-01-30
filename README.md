# UMAP2020
Source codes, raw data and complete results of  paper Off-line vs. On-line Evaluation of Recommender Systems in Small E-commerce submitted to UMAP2020

The paper as well as this repository is based on the preliminary version (https://arxiv.org/abs/1809.03186) presented at REVEAL 2018 vorkshop. For instructions on running the recommending algorithms and off-line evaluation, please refer to https://github.com/lpeska/REVEAL2018 repository. This repository mainly contains data and processed results for on-line evaluation and models aiming to predict on-line performance from off-line results.

- on-line results are processed in OnlineResultsEvaluation.ipynb file

## Abstract
In this paper, we present our work towards comparing on-line and off-line evaluation metrics in the context of small e-commerce recommender systems. Recommending on small e-commerce enterprises is rather challenging due to the lower volume of interactions and low user loyalty, rarely extending beyond a single session. On the other hand, we usually have to deal with lower volumes of objects, which are easier to discover by users through various browsing/searching GUIs.

The main goal of this paper is to determine applicability of off-line evaluation metrics in learning true usability of recommender systems (evaluated on-line in A/B testing). In total 800 variants of recommending algorithms were evaluated off-line w.r.t. 18 metrics covering rating-based, ranking-based, novelty and diversity evaluation. The off-line results were afterwards compared with on-line evaluation of 12 selected recommender variants and based on the results, we tried to learn and utilize an off-line to on-line results prediction model.

Off-line results shown a great variance in performance w.r.t. different metrics with the Pareto front covering 68\% of the approaches. Furthermore, we observed that on-line results are considerably affected by the novelty of users. On-line metrics correlates positively with ranking-based metrics (AUC, MRR, nDCG) for novice users, while too high values of diversity and novelty had a negative impact on the on-line results for them. For users with more visited items, however, the diversity became more important, while ranking-based metrics relevance gradually decrease.
