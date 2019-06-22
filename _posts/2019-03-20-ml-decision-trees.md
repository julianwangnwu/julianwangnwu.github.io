---
title: "ML: Decision trees from scratch"
date: 2019-03-20
permalink: /posts/2019/03/decision-trees/
tags:
  - adavanced
  - machine learning
  - python
---

_Machine Learning: An article explores decision trees and its evaluation._


## Decision Tree Learning Algorithm
Objective: find a shorter tree that is as much consistent with the training examples as possible.

ID3 algorithm: (recursively) choose "most significant" attribute as root of a (sub)tree.
```
function DTL(examples, attributes, default) returens a decision tree
  if examples is empty 
     return default
  else if all examples have the same classification 
     return the classification
  else 
     best-attribute = CHOOSE-ATTRIBUTE(attributes, examples)
     tree = a new decision tree with root best-attribute
     for each value vi of best-attribute do
        examples_i = {elements of examples with best = v_i}
        subtree = DTL(examples_i, (attribute - best), MODE(examples))
        add a branch to tree with label v_i and subtree subtree
     return tree
```

## Hypothesis Evaluation
### Confusion matrix
A confusion matrix, also known as an error matrix,is a specific table layout that allows visualization of the performance of an algorithm, typically a supervised learning one.

It is a special kind of contingency table, with two dimensions ("actual" and "predicted"), and identical sets of "classes" in both dimensions (each combination of dimension and class is a variable in the contingency table).

two rows and two columns that reports the number of false positives, false negatives, true positives, and true negatives. 


<div class="wp-caption aligncenter" style="width: 400px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/confusionmatrix2D.png" width="400" height="400" />
  </p>
  <p class="wp-caption-text">
    <em>Figure 1. 2D Confusion Matrix</em>
  </p>
</div>

Accuracy is a description of systematic errors, a measure of statistical bias; as these cause a difference between a result and a "true" value, ISO calls this trueness.

<div class="wp-caption aligncenter" style="width: 200px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/eq0.png" width="200" height="100" />
  </p>
</div>

precision (also called positive predictive value) is the fraction of relevant instances among the retrieved instances.

<div class="wp-caption aligncenter" style="width: 200px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/eq1.png" width="200" height="100" />
  </p>
</div>
recall (also known as sensitivity) is the fraction of relevant instances that have been retrieved over the total amount of relevant instances.

<div class="wp-caption aligncenter" style="width: 200px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/eq2.png" width="200" height="100" />
  </p>
</div>


In statistical analysis of binary classification, the F1 score (also F-score or F-measure) is a measure of a test's accuracy. It considers both the precision p and the recall r of the test to compute the score: p is the number of correct positive results divided by the number of all positive results returned by the classifier, and r is the number of correct positive results divided by the number of all relevant samples (all samples that should have been identified as positive). The F1 score is the harmonic average of the precision and recall, where an F1 score reaches its best value at 1 (perfect precision and recall) and worst at 0.

<div class="wp-caption aligncenter" style="width: 200px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/eq3.png" width="200" height="100" />
  </p>
</div>

<div class="wp-caption aligncenter" style="width: 750px; border: 0;">
  <p>
    <img class="aligncenter" src="/images/ConfusionMatrix.png" width="750" height="500" />
  </p>
  
  <p class="wp-caption-text">
    <em>Figure 2. Confusion matrix with all performance measurements from <a href="https://en.wikipedia.org/wiki/Confusion_matrix">Wikipedia page</a></em>
  </p>
</div>

