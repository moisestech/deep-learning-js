# 💧 Reducing Overfitting

## [**8.2.3.** Reducing overfitting with weight regularization and visualizing it working](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-8/52)

---

## [**Figure 8.5.** Distribution of the values in the kernel with (panel A) and without (panel B) L2 regularization.](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-8/ch08fig05)

<img src="../../../assets/figures/Figure_8-5.png">

## [**Figure 8.6.** A schematic diagram showing the loss curves from simplified cases of underfitting (panel A), overfitting (panel B), and just-right fitting (panel C) in model training.](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-8/ch08fig06)

<img src="../../../assets/figures/Figure_8-6.png">

---

## [**Table 8.1** An overview of commonly used methods for reducing overfitting in TensorFlow.js](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-8/ch08table01)

<img src="../../../assets/tables/table_8-1.png"/>

---

## **Vocabulary**

- <b>weight regularization</b>
- <b>convnet</b>
- <b>dropout layers<b>
  - is a technique applied to neural networks that randomly sets some of the neurons’ outputs to zero during training. This forces the network to learn better representations of the data by preventing complex interactions between the neurons: Each neuron needs to learn useful features.
- <b>`buildMLPModel()`</b>
- <b>tf.regularizers.l2()</b>
- <b>`l2Rate * l2(kernel)`</b>
- <b>hyperparameter</b>
- <b>tfvis.show.layer()</b>
- <b>quality</b>
- <b>tunable parameters</b>

<link rel="stylesheet" type="text/css" media="all" href="../../../assets/css/custom.css" />

---

from [[_8-2-under-over-fitting-countermeasures]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[_8-2-under-over-fitting-countermeasures]: _8-2-under-over-fitting-countermeasures.md "💧 Under Over Fit Counter Measures"
[//end]: # "Autogenerated link references"
