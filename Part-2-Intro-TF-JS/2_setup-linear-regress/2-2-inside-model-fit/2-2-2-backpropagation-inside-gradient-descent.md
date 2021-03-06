# 🪀 Backprop > Gradient Descent

## [**2.2.2** Backpropagation: Inside gradient descent](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-2/125)

---

### [**Figure 2.9** Illustrating the backpropagation algorithm through a simple linear model with only one updatable weight](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-2/ch02fig09)

<img src="../../../assets/figures/Figure_2-9.png"/>

### [**Figure 2.10** Schematic drawing showing backpropagation from loss to two updatable weights (k and b)](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-2/ch02fig10)

<img src="../../../assets/figures/Figure_2-10.png"/>

---

## **Vocabulary**

- <b>directions</b>
  - which axis and direction does gradient descent move towards as the weights are being computed.
- <b>backpropagation</b>
  - The backpropagation algorithm works by **computing the gradient of the loss function with respect to each weight by the chain rule**,
  - computing the gradient one layer at a time, iterating backward from the last layer to avoid redundant calculations of intermediate terms in the chain rule.
- <b>LayersModel.fit</b>
  - [`<LayersModel.fit>`tf.model.fit()`](https://js.tensorflow.org/api/latest/#tLayersModel.fit)
  - Trains the model for a fixed number of epochs (iterations on a dataset).
- <b>squared error</b>
  - Mean square error function is the basic performance function which affects the network directly.
  - Reducing of such error will result in an efficient system.
- <b>gradient of loss with respect to V</b>
  - An error gradient is the direction and magnitude calculated during the training of a neural network that is used to update the network weights in the right direction and by the right amount.
- <b>opposite</b>
- <b>chain rule</b>
- <b>multiple input features</b>
- <b>basics</b>

<link rel="stylesheet" type="text/css" media="all" href="../../../assets/css/custom.css" />

---

from [[_2-2-inside-model-fit]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[_2-2-inside-model-fit]: _2-2-inside-model-fit.md "🪀 Inside Model Fit"
[//end]: # "Autogenerated link references"
