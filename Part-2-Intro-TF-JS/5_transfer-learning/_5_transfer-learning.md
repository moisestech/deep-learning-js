# 🟦 TRANSFER LEARNING

## [**Chapter 5.** Transfer learning: Reusing pretrained neural networks](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-5/)

## This chapter covers

- What transfer learning is and why it is better than training models from scratch for many types of problems
- How to leverage the feature-extraction power of state-of-the-art pre-trained convnets by converting them from Keras to TensorFlow.js
- The detailed mechanisms of transfer-learning techniques including layer freezing, creating new transfer heads, and fine-tuning
- How to use transfer learning to train a simple object-detection model in TensorFlow.js

## Summary

- Transfer learning is the process of reusing a pretrained model or a part of it on a learning task related to, but different from, the one that the model was originally trained for. This reusing speeds up the new learning task.
- In practical applications of transfer learning, people often reuse convnets that have been trained on very large classification datasets, such as MobileNet trained on the ImageNet dataset. Due to the sheer size of the original dataset and the diversity of the examples it contains, such pretrained models bring with them convolutional layers that are powerful, general-purpose feature extractors for a wide variety of compute-vision problems. Such layers are difficult, if not impossible, to train with the small amount of data that are available in typical transfer-learning problems.
- We discussed several general approaches of transfer learning in TensorFlow.js, which differ from each other in terms of 1) whether new layers are created as the “new head” for transfer learning and 2) whether the transfer learning is done with one model instance or two. Each approach has its pros and cons and is suited for different use cases (see table 5.1).
- By setting the trainable attribute of a model’s layer, we can prevent its weights from being updated during training (Model.fit() calls). This is referred to as freezing and is used to “protect” the base model’s feature-extraction layers during transfer learning.
- In some transfer-learning problems, we can boost the new model’s performance by unfreezing a few top layers of the base model after an initial phase of training. This reflects the adaptation of the unfrozen layers to the unique features in the new dataset.
- Transfer learning is a versatile and flexible technique. The base model can help us solve problems that are different from the one that it is originally trained on. We illustrated this point by showing how to train an object-detection model based on MobileNet.
- Loss functions in TensorFlow.js can be defined as custom JavaScript functions that operate on tensor inputs and outputs. As we showed in the simple object-detection example, custom loss functions are often needed to solve practical machine-learning problems.

---

## **Vocabulary**

- <b>images</b>
- <b>training data</b>
- <b>MobileNet</b>
- <b>classification</b>
- <b>labeled pictures</b>

<link rel="stylesheet" type="text/css" media="all" href="../../../assets/css/custom.css" />

---

from [[_part-2-intro-ts-js]]
