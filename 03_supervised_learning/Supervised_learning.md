# Supervised Learning Overview

Supervised learning is a type of machine learning where a model is trained on a labeled dataset. Each training example consists of an input and a corresponding correct output (label). The goal is for the model to learn a function that maps inputs to the correct outputs.

---

## Key Characteristics

- Uses labeled datasets: input (x) and output (y)  
- Learns a mapping function f(x; θ) that minimizes prediction error

- Two major tasks:
  - **Classification**: Predict discrete labels (e.g., dog, cat)
  - **Regression**: Predict continuous values (e.g., house prices)

---

## Mathematical Formulation

Given a dataset:

D = { (x₁, y₁), (x₂, y₂), ..., (x_N, y_N) }

The model aims to minimize the empirical loss:

min_θ (1/N) * Σᵢ=1ⁿ L(f(xᵢ; θ), yᵢ)

Where:
- `f`: the model (e.g., neural network)
- `θ`: model parameters
- `L`: the loss function (e.g., cross-entropy or MSE)

---

## Common Models

- 1. Linear Regression
- 2. Logistic Regression
- 3. Support Vector Machines (SVM)
- 4. Decision Trees / Random Forests
- 5. Neural Networks (MLP, CNN, RNN)

---

## Application Examples

| Task              | Input Example        | Output (Label)              |
|-------------------|----------------------|-----------------------------|
| Image Classification | Image               | Category (e.g., dog, cat)    |
| Spam Detection     | Email text           | Spam / Not spam             |
| House Price Prediction | Area, age, location | Price (real number)         |

---

## Typical Workflow

1. Prepare labeled dataset
2. Choose a model
3. Define a loss function
4. Train using an optimizer (e.g., gradient descent)
5. Evaluate using metrics like accuracy, RMSE

---

## Challenges

- Labeling data can be expensive
- Risk of overfitting on small datasets
- Dataset bias can impact generalization

---

## References

- [Introduction to Supervised Learning - scikit-learn](https://scikit-learn.org/stable/supervised_learning.html)

- [Deep Learning Book by Ian Goodfellow - Chapter 5](https://www.deeplearningbook.org/)

- [Andrew Ng – Machine Learning (Coursera, classic 2011 Stanford course)**](https://www.coursera.org/learn/machine-learning)

- [Kaggle – Intro to Machine Learning Micro-course**](https://www.kaggle.com/learn/intro-to-machine-learning)

- [Stanford CS231n Notes – “Image Classification: A Data-Driven Approach”**](https://cs231n.github.io/classification/)


---
