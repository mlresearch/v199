---
title: A Dataset Perspective on Offline Reinforcement Learning
abstract: The application of Reinforcement Learning (RL) in real world environments
  can be expensive or risky due to sub-optimal policies during training. In Offline
  RL, this problem is avoided since interactions with an environment are prohibited.
  Policies are learned from a given dataset, which solely determines their performance.
  Despite this fact, how dataset characteristics influence Offline RL algorithms is
  still hardly investigated. The dataset characteristics are determined by the behavioral
  policy that samples this dataset. Therefore, we define characteristics of behavioral
  policies as exploratory for yielding high expected information in their interaction
  with the Markov Decision Process (MDP) and as exploitative for having high expected
  return. We implement two corresponding empirical measures for the datasets sampled
  by the behavioral policy in deterministic MDPs. The first empirical measure SACo
  is defined by the normalized unique state-action pairs and captures exploration.
  The second empirical measure TQ is defined by the normalized average trajectory
  return and captures exploitation. Empirical evaluations show the effectiveness of
  TQ and SACo. In large-scale experiments using our proposed measures, we show that
  the unconstrained off-policy Deep Q-Network family requires datasets with high SACo
  to find a good policy. Furthermore, experiments show that policy constraint algorithms
  perform well on datasets with high TQ and SACo. Finally, the experiments show, that
  purely dataset-constrained Behavioral Cloning performs competitively to the best
  Offline RL algorithms for datasets with high TQ.
video: https://youtu.be/gYOieDpvhew
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: schweighofer22a
month: 0
tex_title: A Dataset Perspective on Offline Reinforcement Learning
firstpage: 470
lastpage: 517
page: 470-517
order: 470
cycles: false
bibtex_author: Schweighofer, Kajetan and Dinu, Marius-constantin and Radler, Andreas
  and Hofmarcher, Markus and Patil, Vihang Prakash and Bitto-nemling, Angela and Eghbal-zadeh,
  Hamid and Hochreiter, Sepp
author:
- given: Kajetan
  family: Schweighofer
- given: Marius-constantin
  family: Dinu
- given: Andreas
  family: Radler
- given: Markus
  family: Hofmarcher
- given: Vihang Prakash
  family: Patil
- given: Angela
  family: Bitto-nemling
- given: Hamid
  family: Eghbal-zadeh
- given: Sepp
  family: Hochreiter
date: 2022-11-28
address:
container-title: Proceedings of The 1st Conference on Lifelong Learning Agents
volume: '199'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 11
  - 28
pdf: https://proceedings.mlr.press/v199/schweighofer22a/schweighofer22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
