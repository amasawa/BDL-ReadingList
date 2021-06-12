# Bayesian Deep Learning Reading list

## Preface

DBL is a sort of model that integrating process states to increase the confidence of Deep models. Depending on the experimental setting, we can divide the DBL models into three Tasks:

* **Generative models in CV**
* **Uncertainty quantization in Machine Learning**
  * partially or completely focus on **OoD and Active Learning Tasks**
  *  **Stochastic Process Models** and **BNNs**
* **Time series Problems**

Many works have been done to analyze the connection between Deep models and Statistic property, including: 

* **Surveys**
  
  * [Uncertainty in Deep Learning](https://mlg.eng.cam.ac.uk/yarin/thesis/thesis.pdf)
  * [A Survey on Bayesian Deep Learning](https://dl.acm.org/doi/pdf/10.1145/3409383)
  
* **Workshops**:
  
  * [NeurIPS](http://bayesiandeeplearning.org/2019/index.html)
  
* **Scholars & Groups**:
  
  * [OATML: Oxford Applied And Theore$Yical Machine Learning Group](https://oatml.cs.ox.ac.uk/tags/BDL.html#title)
  
  * [Andrew Gordon Wilson, NYU](https://cims.nyu.edu/~andrewgw/)
  
  

## 1. Machine Learning

### 1.1 Uncertainty Quantization

Here Thesis marked in  $\spadesuit$  are some baselines for OoD and $\bigstar$ for Activate Learning Tasks.

* **Arxiv21**: Uncertainty Baselines: Benchmarks for uncertainty & robustness in deep learning 
  * [**Paper**](https://arxiv.org/abs/2106.04015), [**Code**](https://github.com/google/uncertainty-baselines)
* **NIPS17**: What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?  
  * [**Paper**](https://proceedings.neurips.cc/paper/2017/file/2650d6089a6d640c5e85b2b88265dc2b-Paper.pdf), [**Code1**](https://github.com/ShellingFord221/My-implementation-of-What-Uncertainties-Do-We-Need-in-Bayesian-Deep-Learning-for-Computer-Vision),  [**Code2**]()
* **AISTATS19**: Calibrating Deep Convolutional Gaussian Processes, 
  * [**Paper**](https://ctn.zuckermaninstitute.columbia.edu/sites/default/files/content/Publications/2018/Tran%20%28Cunningham%29%2C%20Calibrating%20Deep%20Convolutional%20Gaussian%20Processes.pdf),[**Code**](https://github.com/ebonilla/convolutional_deep_gp_random_features)
* **NeurIPS20**: Simple and Principled Uncertainty Estimation with Deterministic Deep Learning via Distance Awareness,
  *  [**Paper**](http://www.gatsby.ucl.ac.uk/~balaji/udl2020/accepted-papers/UDL2020-paper-057.pdf),[**Code**](https://github.com/google/uncertainty-baselines/tree/master/baselines)
* **ICML20-DUQ:** Uncertainty Estimation Using a Single Deep Deterministic Neural Network, 
  * [**Paper**](http://proceedings.mlr.press/v119/van-amersfoort20a/van-amersfoort20a.pdf),[**Code1**](https://github.com/y0ast/deterministic-uncertainty-quantification) , [**Code2**](https://github.com/mr3543/deterministic_uncertainty_quantification)
* $\spadesuit$ **NeurIPS20**: Energy-based Out-of-distribution Detection, 
  * [**Paper**](https://arxiv.org/pdf/2010.03759.pdf),[**Code**](https://github.com/wetliu/energy_ood)
* **Arxiv21-DDU:** Deterministic Neural Networks with Appropriate Inductive Biases Capture Epistemic and Aleatoric Uncertainty,
  *  [**Paper**](https://arxiv.org/pdf/2102.11582.pdf),[**Code**](https://github.com/omegafragger/DDU)

### 1.2 Statistic Models

## 2. Computer Vision

### 2.1 Generative model: AIR

### 2.2 Generative models: VAE & GAN

## 3. Time Series
