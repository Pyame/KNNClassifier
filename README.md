# KNNClassifier

## Introduction
**KNN classifier** is simple *Machine Learning* algorithm.
It belongs to supervised learning techniques.

This Classifier is called *lazy learner algorithm*. It is not because of no reasons. 
There are some examples:
* it looks for similarities between "new data" and cases in training set, then put the new object into best fitting category, basing on 
which category is it most similar to,
* it doesn't learn from training set immediately, but it looks for data at the moment of classification. It means that every new object that has to be classified must be *"compared"* with every class and after that it will be fitted to most similar one,
* **non-parametric algorithm** - means no assumption on base dataset.

## Work process
**KNN classifier** is performed in several steps and can be explained this way:
1. Decide how many **"neighbors"** will be taken into consideration (it will be our **K**),
2. Do some math, calculate the **euclidean distance** of K number of neighbors.
3. Take the K nearest neighbors, where euclidean distance is *"closest"*.
4. Every parameter has to have its "value", it is called **data points**, it has to be counted.
5. **Assign new data points** to category which number of neighbors is highest.

![Alt text](classes.png)
![Alt text](euclidean.png)
![Alt text](distance.png)