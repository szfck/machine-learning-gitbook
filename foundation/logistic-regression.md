# Logistic Regression

Logistic regression is a learning algorithm used in a supervised learning problem when the output $y$ are all either zero or one. The goal of logistic regression is to minimize the error between its predictions and training data.

## Eg. Cat vs No - cat

Given an image represented by a feature vector $x$, the algorithm will evaluate the probability of a cat being in that image.


$$
Given \ x, \hat{y} = P(y = 1 | x), where \  0 \leq \hat{y} \leq 1 
$$

* The input features vector: $x \in \mathbb{R}^{n_x}$, where $n_x$ is the number of features
* The training label: $y \in 0,1$
* The weights: $w \in \mathbb{R}^{n_x}$, where 𝑛𝑥 is the number of features
* The threshold: $b \in \mathbb{R}$
* The output: $\hat{y} = \sigma(wT_x + b)$
* Sigmoid function: $s = \sigma(wT_x + b) = \sigma(z)= \frac{1}{1 + e^{-z}}$

![](/assets/Snip20180126_8.png)


























