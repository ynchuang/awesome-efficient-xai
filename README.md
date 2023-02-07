# Awesome-Efficient-XAI-Techniques[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a curated, but probably biased and incomplete, list of awesome Efficient XAI resources.

If you want to contribute to this list, feel free to pull a request. Also you can contact [Yu-Neng Chuang](https://www.linkedin.com/in/ync/) and [Guanchu Wang](https://guanchuwang.github.io/home/) from the [Data Lab](https://cs.rice.edu/~xh37/index.html) at Rice University through email: ynchuang@rice.edu and guanchu.wang@rice.edu.

## What is XAI? Why do we focus on the Efficiency of XAI?

Despite the remarkable achievement of deep neural networks (DNNs) in a variety of fields, the black-box nature of DNNs still limits its deployment in domains where model explanations are required for acquiring trustful results, such as the healthcare and finance domains.
Explainable machine learning aims to improve the transparency of DNNs, providing human-understandable decisions in the real-world scenarios.
On the one hand, XAI enables the decisions of DNNs to be trustworthy; on the other hand, it alleviates concerns about the use of personal data.

Post-hoc explanation reveals faithful and effective instance-based explanation under theoretical guarantee. 
However, the high computational complexity sets a barrier to deployment on real-world systems, which suffer from sampling variability. 
Providing a real-time explanation is still a remaining challenge in preserving the trade-off between efficacy and efficiency for a post-hoc explanation method.


## Table of Contents

* [Review and General Papers](#review-and-general-papers)

* [Non-amortized acceleration](#non-amortized-acceleration)
    * Data-centric Acceleration
    * Model-centric Acceleration

* [Amortized acceleration](#amortized-acceleration)
    * Predictive-driven Method
    * Generative-driven Method
    * Reinforcement Method

* [Acceleration of Feature Interaction Detection](#acceleration-of-feature-interaction-detection)
    
* [XAI Packages and Toolkits](#xai-packages-and-toolkits)


* [Other XAI Relevant Resources](#other-xai-relevant-resources)


## Review and General Papers

* [Interpretable machine learning](https://books.google.com/books?hl=zh-CN&lr=&id=jBm3DwAAQBAJ&oi=fnd&pg=PP1&ots=EgyQVlKBW-&sig=U-KcrXZmUOI3bMNahFWP2as6WEw#v=onepage&q&f=false)
* [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
* [Explainable Recommendation: A Survey and New Perspectives](https://arxiv.org/pdf/1804.11192.pdf)
* [Counterfactual Explanations and Algorithmic Recourses for Machine Learning: A Review](https://arxiv.org/pdf/2010.10596.pdf)

## Non-amortized acceleration

### Data-centric Acceleration

* [Accelerating Shapley Explanation via Contributive cooperator Selection](https://arxiv.org/pdf/2206.08529.pdf)
* [Groupshapley: Efficient Prediction Explanation with Shapley Values for Feature Group](https://arxiv.org/pdf/2106.12228.pdf)
* [Polynomial Calculation of the Shapley Value based on Sampling](https://dl.acm.org/doi/10.1016/j.cor.2008.04.004)
* [Antithetic and Monte Carlo Kernel Estimators for Partial Rankings](https://arxiv.org/pdf/1807.00400.pdf)
* [Sampling Permutations for Shapley Value Estimation](https://www.jmlr.org/papers/volume23/21-0439/21-0439.pdf)
* [Scaling Guarantees for Nearest Counterfactual Explanations](https://arxiv.org/pdf/2010.04965.pdf)
* [Optimal Counterfactual Explanations in Tree Ensembles](https://arxiv.org/pdf/2106.06631.pdf)
* [Counterfactual Explanations for Oblique Decision Trees: Exact, Efficient Algorithms](https://arxiv.org/pdf/2103.01096.pdf)
* [Efficient Search for Diverse Coherent Explanations](https://arxiv.org/pdf/1901.04909.pdf)
* [Model-Agnostic Counterfactual Explanations of Recommendations](https://dl.acm.org/doi/fullHtml/10.1145/3450613.3456846)

### Model-centric Acceleration

* [DACE: Distribution-Aware Counterfactual Explanation by Mixed-Integer Linear Optimization](https://www.ijcai.org/proceedings/2020/0395.pdf)
* [Multi-Objective Counterfactual Explanations](https://arxiv.org/pdf/2004.11165.pdf)
* [Efficient computation of counterfactual explanations and counterfactual metrics of prototype-based classifiers](https://dl.acm.org/doi/abs/10.1016/j.neucom.2021.04.129)
* [Influence-Driven Explanations for Bayesian Network Classiers](https://arxiv.org/pdf/2012.05773.pdf)
* [Interpretable Counterfactual Explanations Guided by Prototypes](https://arxiv.org/pdf/1907.02584.pdf)
* [Counterfactual Shapley Additive Explanations](https://arxiv.org/pdf/2110.14270.pdf)
<!-- Approximation-driven -->
* [Explaining Deep Neural Networks with a Polynomial Time Algorithm for Shapley Values Approximation](https://arxiv.org/pdf/1903.10992.pdf)
* [Efficient Computation and Analysis of Distributional Shapley Values](https://arxiv.org/pdf/2007.01357.pdf)
* [Improving KernelSHAP: Practical Shapley Value Estimation via Linear Regression](https://arxiv.org/pdf/2012.01536.pdf)
* [Improved Feature Importance Computations for Tree Models: Shapley vs. Banzhaf](https://arxiv.org/pdf/2108.04126.pdf)
* [Fast TreeSHAP: Accelerating SHAP Value Computation for Trees](https://arxiv.org/pdf/2109.09847.pdf)
* [L-Shapley and C-Shapley: Efficient Model Interpretation for Structured Data](https://openreview.net/forum?id=S1E3Ko09F7)

## Amortized acceleration

### Predictive-driven Method

* [FastSHAP: Real-Time Shapley Value Estimation](https://arxiv.org/pdf/2107.07436.pdf)
* [CoRTX: Contrastive Framework for Real-time Explanation](https://openreview.net/forum?id=L2MUOUp0beo)
* [Learning to Explain: An Information-Theoretic Perspective on Model Interpretation](https://arxiv.org/pdf/1802.07814.pdf)
* [CXPlain: Causal Explanations for Model Interpretation under Uncertainty](https://arxiv.org/pdf/1910.12336.pdf)
* [Investigating Causal Relations by Econometric Models and Cross-spectral Methods](http://tyigit.bilkent.edu.tr/metrics2/read/Investigating%20%20Causal%20Relations%20by%20Econometric%20Models%20and%20Cross-Spectral%20Methods.pdf)
* [Shapley Explanation Networks](https://arxiv.org/pdf/2104.02297.pdf)
* [Learning to Explain with Complemental Examples](https://arxiv.org/pdf/1812.01280.pdf)
* [Attention-like feature explanation for tabular data](https://arxiv.org/pdf/2108.04855.pdf)
* [Efficient Explanations from Empirical Explainers](https://arxiv.org/pdf/2103.15429.pdf)
* [Fast Axiomatic Attribution for Neural Networks](https://arxiv.org/pdf/2111.07668.pdf)


### Generative-driven Method

* [Model-Based Counterfactual Synthesizer for Interpretation](https://arxiv.org/pdf/2106.08971.pdf)
* [Explanation by Progressive Exaggeration](https://arxiv.org/pdf/1911.00483.pdf)
* [Explaining the Black-box Smoothly- A Counterfactual Approach](https://arxiv.org/pdf/2101.04230.pdf)
* [Getting a CLUE: A Method for Explaining Uncertainty Estimates](https://arxiv.org/pdf/2006.06848.pdf)
* [Cycle-Consistent Counterfactuals by Latent Transformations](https://arxiv.org/pdf/2203.15064.pdf)
* [Learning Model-Agnostic Counterfactual Explanations for Tabular Data](https://arxiv.org/pdf/1910.09398.pdf)
* [Towards Realistic Individual Recourse and Actionable Explanations in Black-Box Decision Making Systems](https://arxiv.org/pdf/1907.09615.pdf)
* [Beyond Trivial Counterfactual Explanations with Diverse Valuable Explanations](https://arxiv.org/pdf/2103.10226.pdf)
* [VCNet: A Self-explaining Model for Realistic Counterfactual Generation](https://2022.ecmlpkdd.org/wp-content/uploads/2022/09/sub_633.pdf)
* [CRUDS: Counterfactual Recourse Using Disentangled Subspaces](https://finale.seas.harvard.edu/files/finale/files/cruds-_counterfactual_recourse_using_disentangled_subspaces.pdf)
* [Preserving Causal Constraints in Counterfactual Explanations for Machine Learning Classifiers](https://arxiv.org/pdf/1912.03277.pdf)
* [xGEMs: Generating Examplars to Explain Black-Box Models](https://arxiv.org/pdf/1806.08867.pdf)
* [Generative Counterfactuals for Neural Networks via Attribute-Informed Perturbation](https://arxiv.org/pdf/2101.06930.pdf)
* [CLEAR: Generative Counterfactual Explanations on Graphs](https://arxiv.org/pdf/2210.08443.pdf)


### Reinforcement Method

* [ReLAX: Reinforcement Learning Agent eXplainer for Arbitrary Predictive Models](https://arxiv.org/pdf/2110.11960.pdf)
* [Amortized Generation of Sequential Algorithmic Recourses for Black-Box Models](https://ojs.aaai.org/index.php/AAAI/article/view/20828)

## Acceleration of Feature Interaction Detection

* [Neural Interaction Transparency (NIT): Disentangling Learned Interactions for Improved Interpretability](https://proceedings.neurips.cc/paper/2018/file/74378afe5e8b20910cf1f939e57f0480-Paper.pdf)
* [Detecting Statistical Interactions from Neural Network Weights](https://arxiv.org/pdf/1705.04977.pdf)
* [Towards Interaction Detection Using Topological Analysis on Neural Networks](https://proceedings.neurips.cc/paper/2020/file/473803f0f2ebd77d83ee60daaa61f381-Paper.pdf)
* [Feature Interaction Interpretability: A Case for Explaining Ad-Recommendation Systems via Neural Interaction Detection](https://openreview.net/forum?id=BkgnhTEtDS)
* [Faith-Shap: The Faithful Shapley Interaction Index](https://arxiv.org/pdf/2203.00870.pdf)
* [The Shapley Taylor Interaction Index](http://proceedings.mlr.press/v119/sundararajan20a/sundararajan20a.pdf)


# XAI Packages and Toolkits

* [XDeep: an Open-source Python Library for Interpretable Machine Learning](https://github.com/datamllab/xdeep)
* [SHAP: A a Game Theoretic Package to Explain Machine Learning Models](https://github.com/slundberg/shap)
* [Captum: Model Interpretability for PyTorch](https://captum.ai/)
* [OmniXAI: A Library for Explainable AI](https://github.com/salesforce/OmniXAI)
* [AIX 360: An Open-source Toolkit of Explainable Machine Learning](https://aix360.mybluemix.net/)
* [InterpretML: A Toolkit to Help Understand Models and Enable Responsible Machine Learning](https://interpret.ml/)
* [Alibi Explain: An Open-source Python library for Machine Learning Model Inspection and Interpretation](https://github.com/SeldonIO/alibi)
* [OpenXAI: Towards a Transparent Evaluation of Model Explanations](https://github.com/AI4LIFE-GROUP/OpenXAI)

# Other XAI Relevant Resources

* [Awesome Interpretable Machine Learning](https://github.com/lopusz/awesome-interpretable-machine-learning)
* [Awesome Machine Learning Interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)
* [Awesome Fairness in AI](https://github.com/datamllab/awesome-fairness-in-ai)
* [A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/)
* [A Chinese Open Course of Interpretable Machine Learning](https://github.com/TommyZihao/zihao_course/tree/main/XAI)
