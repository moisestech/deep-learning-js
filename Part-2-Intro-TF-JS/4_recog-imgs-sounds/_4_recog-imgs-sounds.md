# ♦️ RECOG IMG MP3

## [**Chapter 4.** Recognizing images and sounds using convnets](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-4/)

## This chapter covers

- How images and other perceptual data, such as audio, are **represented as multidimensional tensors**
- What **convnets** are, how they work, and **why they are especially suitable for machine-learning tasks involving images**
- How to **write and train a convnet in TensorFlow.js** to solve the task of classifying hand-written digits
- How to **train models in Node.js** to achieve faster training speeds
- How to **use convnets on audio data for spoken-word recognition**

## Summary

- **Convnets extract 2D spatial features** from input images with a hierarchy of stacked conv2d and maxPooling2d layers.
- **conv2d layers are multichannel, tunable spatial filters**.
  - They have the properties of **locality** and **parameter sharing**, which make them **powerful feature extractors and efficient representational transforms**.
- maxPooling2d layers reduce the size of the input image tensor by calculating the maximum within fixed-size windows, achieving better positional invariance.
- The conv2d-maxPooling2d “tower” of a convnet usually ends in a flatten layer, which is followed by an MLP made of dense layers for classification or regression tasks.
- With its restricted resources, the browser is only suitable for training small models. To train larger models, it is recommended you use tfjs-node, the Node.js version of TensorFlow.js; tfjs-node can use the same CPU- and GPU-parallelized kernels used by the Python version of TensorFlow.
- With greater model capacities comes greater risks of overfitting. Overfitting can be ameliorated by adding dropout layers in a convnet. Dropout layers randomly zero-out a given fraction of the input elements during training.
- Convnets are useful not only for computer vision tasks. When audio signals are represented as spectrograms, convnets can be applied on them to achieve good classification accuracies as well.

---

## **Vocabulary**

---

from [[_part-2-intro-ts-js]]
