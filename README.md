# Classification Predictive Modeling

A classification problem in machine learning consists of predicting a class label from a given example of input data.

In order to model classification, you need a training dataset that includes many examples of inputs and outputs.

In a model, examples of input data are mapped to specific class labels based on the training dataset. Thus, the training dataset must be sufficient to represent the problem and include many examples of each class label. 

 

## Binary Classification

Binary classification refers to those classification tasks that have two class labels.

Examples include:

* Email spam detection (spam or not).
* Churn prediction (churn or not).
* Conversion prediction (buy or not).

Most binary classification tasks involve classifying one state as normal and the other as abnormal.


 

## Multi-Class Classification

Multi-class classification refers to those classification tasks that have more than two class labels.

Examples include:

* Face classification.
* Plant species classification.
* Optical character recognition.

With multi-class classification, normal and abnormal outcomes do not exist as they do in binary classification. As an alternative, examples are classified according to a set of known classes.

Some problems may have a large number of class labels. As an example, in a face recognition system, a model may identify a picture as belonging to one of thousands or tens of thousands of faces.

A classification task may involve one of four types; they are as follows:

* Binary Classification
* Multi-Class Classification
* Multi-Label Classification
* Imbalanced Classification

 

## Multi-Label Classification
The multi-label classification aspect occurs when there are two or more class labels, and each example can be assigned one or more class labels.

It differs from binary classification and multiclass classification, in which each example is assigned a class label.

Models that predict multiple outcomes in multi-label classification tasks are commonly based on a Bernoulli probability distribution for each output. In essence, this is a model that predicts the binary classification of every example.

 

## Imbalanced Classification

When examples in different classes are unequally distributed, this is called imbalanced classification.

An imbalanced classification task is one in which the majority of examples in the training dataset represent the normal class while a minority represents the abnormal class.

Examples include:

* Fraud detection.
* Outlier detection.
* Medical diagnostic tests.

## Credits
[https://keras.io/api/applications/](https://keras.io/api/applications/)

[https://machinelearningmastery.com/](https://machinelearningmastery.com/)
 
