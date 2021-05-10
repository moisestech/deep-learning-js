# ♒️ NON-LINEARITY

## [**Chapter 3.** Adding nonlinearity: Beyond weighted sums](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-3/)

## This chapter covers

- What **nonlinearity** is and how nonlinearity in hidden layers of a neural network **enhances the network’s capacity and leads to better prediction accuracies**
- What **hyperparameters** are and **methods for tuning them**
- **Binary classification through nonlinearity** at the output layer, introduced with the phishing-website-detection example
- **Multiclass classification** and how it differs from binary classification, introduced with the **iris-flower example**

---

## **Summary**

- **Classification** tasks are different from regression tasks in that they involve making discrete predictions.
- There are **two types of classification**:
  - In **binary classification**, there are two possible classes for a given input
  - whereas in **multiclass classification**, there are three or more.
- **Binary classification** can usually be viewed as detecting a certain type of event or object of significance, called positives, among all the input examples. When viewed this way, we can use metrics such as precision, recall, and FPR, in addition to accuracy, to quantify various aspects of a binary classifier’s behavior.
  - The **trade-off** between the need to catch all positive examples and the need to minimize false positives (false alarms) is common in binary-classification tasks. The ROC curve, along with the associated AUC metric, is a technique that helps us quantify and visualize this relation.
  - A **neural network created for binary classification** should use the sigmoid activation in its last (output) layer and use binary cross entropy as the loss function during training.
  - To create a **neural network for multiclass classification**, the output target is usually represented by one-hot encoding.
  - The neural network ought to use softmax activation in its output layer and be trained using the categorical cross-entropy loss function.
  - For **multiclass classification**, **confusion matrices** can provide more fine-grained information regarding the mistakes made by the model than accuracy can.
  - **Table 3.6** summarizes **recommended methodologies for the most common types of machine-learning** problems we have seen so far (regression, binary classification, and multiclass classification).
- **Hyperparameters** are configurations concerning a machine-learning model’s structure, properties of its layer, and its training process. They are distinct from the **model’s weight parameters** in that:
  1. they do not change during the model’s training process
  2. they are often discrete.
  - **Hyperparameter optimization** is the process in which values of the hyperparameters are sought in order to minimize a loss on the validation dataset.
  - **Hyperparameter optimization** is still an active area of research. Currently, the most frequently used methods include **grid search**, **random search**, and **Bayesian methods**.

---

## **Exercises**

---

## **Vocabulary**

- **features**
- **labels**
- **weighted sum**
- **accuracy**
- **problems**
- **Boston-housing dataset**
- **models**
- **training data**
- **quality**

<link rel="stylesheet" type="text/css" media="all" href="../../../assets/css/custom.css" />

---

from [[_part-2-intro-ts-js]]
