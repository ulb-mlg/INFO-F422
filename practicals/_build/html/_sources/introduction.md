# Introduction
## Welcome
Welcome to the practicals handbook of the *Statistical Foundations of Machine Learning* course, part of the Master's program in Computer Science at ULB. This course provides the essential mathematical and algorithmic foundations behind the modern techniques used in machine learning, with a strong focus on statistics, probabilistic modeling, and regression/classification methods. It is the perfect starting point for anyone aiming to understand, build, and evaluate predictive models rigorously. The present document aims at bringing additional examples, tools and exercises to help understanding the main course's contents.

---

## Why This Book?

Machine learning is not magic. It is grounded in solid mathematical ideas, especially probability theory, statistics, linear algebra, and optimization. Understanding **how and why** algorithms work is crucial for designing good systems that are not only performant but also interpretable and reliable.

This book will:

- Build your **intuition** for probabilistic reasoning and statistical inference.
- Introduce **core regression and classification models**, from linear regression to neural networks.
- Teach you how to **implement algorithms**, visualize results, and understand performance metrics.
- Provide **practical tools and code exercises** using Python and popular libraries such as NumPy, Matplotlib, scikit-learn, and PyTorch.
- Develop your ability to **choose, analyze, and compare models**, considering trade-offs like bias/variance, overfitting, and interpretability.

Whether your goal is to become a data scientist, ML engineer, or researcher, these foundations will serve as the most important base for more advanced courses and projects.

---

## Course Overview

As 2026 is the the first year of exploitation of this handbook, chapters will be delivered practical after practicals. If you notice any mistake, typo, unclarity, please [send me and email](mailto:pascal.tribel@ulb.be) !
Here's what you can expect:

### Introduction to Probabilistic Methods and Monte Carlo Simulations
We start with the building blocks of randomness and probability:
- Simulating data with `NumPy`
- Visualizing distributions with `Matplotlib`
- Understanding Monte Carlo simulations
- Working with **multivariate Gaussians**
- Learning about **minimization** in statistical modeling
- Exploring **Gaussian Mixture Models**

---

### Linear Models
From classical regression to more flexible transformations:
- Ordinary Least Squares (OLS) regression
- Analyzing residuals and model assumptions
- Polynomial and **Radial Basis Function (RBF)** transformations
- Ridge regression and the role of regularization

---

### Preprocessing, Local Models and Tree-Based Models
Preparing your data and working with interpretable machine learning models:
- Data preprocessing: normalization, handling missing data
- **k-Nearest Neighbors (kNN)** for regression
- **Decision trees** and **random forests**
- Using **scikit-learn pipelines**
- Understanding the **bias-variance tradeoff** in practice

---

### Neural Networks for Regression
Deep learning in its most intuitive form:
- Normalization and standardization for stable learning
- MLPs (Multilayer Perceptrons) for regression tasks
- Cost functions and model training
- **Matrix-based backpropagation**
- Introduction to **CNNs**
- Dealing with **overfitting**, **cross-validation**
- Model persistence: saving and loading in **PyTorch**

---

### Ensemble Models and Feature Selection
Combining models and selecting the most useful inputs:
- Error decomposition and performance metrics
- **Filter, wrapper, and embedded** feature selection
- Building **ensembles** of models for improved accuracy

---

### Classification
From regression to classification, we shift the focus:
- Evaluation metrics for classification (accuracy, precision, recall, F1)
- **Bayes classifier** and probabilistic foundations
- **Logistic regression** and ROC curves
- Working with **unequal costs**
- Alternative classification models

---

## Practical Exercises
This handbook serves as the practicals reference for the course. The [theorecical handbook](https://www.researchgate.net/publication/242692234_Statistical_foundations_of_machine_learning_the_handbook) remains the main reference. We want to focus here in the implementations, the algorithms and the existing libraries for implementing the topics covered in the course. The student should refer as much as possible to the theoretical handbook before delving into the coding. Here, we try, as much as possible, to include:
- **Hands-on coding exercises**
- **Mini-projects and simulations**
- **Graphical visualizations** of models and results
- Opportunities to **experiment** with real-world datasets

Doing the exercises is **not optional** if you want to truly master the material. They are designed to:
- Reinforce theoretical concepts
- Develop your implementation skills
- Sharpen your critical thinking about model performance and assumptions

---

## Final Notes

This is a **theory-meets-practice** course. You'll build up solid statistical thinking and programming fluency, while also learning to critically assess and apply machine learning models. Every part of the course prepares you for future work in AI, Data Science, or scientific computing.

**Take it seriously. Be curious. Challenge your understanding. And above all: have fun exploring the possibilities of statistical thinking in machine learning.**

Let's begin!