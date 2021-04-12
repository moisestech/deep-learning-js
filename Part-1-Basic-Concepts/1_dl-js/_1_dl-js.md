# 🌱 1 DL and JS

## [**Chapter 1.** Deep learning and JavaScript](https://livebook.manning.com/book/deep-learning-with-javascript/chapter-1/)

## This Chapter Covers

- What **deep learning** is and how it is related to artificial intelligence (AI) and machine learning
- **What makes deep learning stand out** among various machine-learning techniques, and the factors that led to the current “deep-learning revolution”
- The reasons for doing deep learning in JavaScript using **TensorFlow.js**
- The overall organization of this book

---

## **Summary**

- AI is the **study of automating cognitive tasks**.
  - Machine learning is a subfield of AI in which **rules** for performing a task such as image classification are **discovered automatically by learning from examples in the training data**.
- A **central problem** in machine learning is how to transform the original representation of data into a **representation more amenable to solving the task**.
- **Neural networks** are an approach in machine learning wherein the **transformation of data** representation is **performed by successive steps (or layers) of mathematical operations**.
  - The field of **deep learning** concerns deep neural networks— neural networks with **many layers**.
- Thanks to enhancements in **hardware**, increased availability of **labeled data**, and **advances in algorithms**, the field of deep learning has made astonishing progress since the early 2010s, **solving previously unsolvable problems** and creating exciting new opportunities.
- **JavaScript** and the web browser are a **suitable environment** for deploying and training deep neural networks.
- TensorFlow.js, the focus of this book, is a comprehensive, versatile, and **powerful open source library for deep learning in JavaScript**.

---

## Exercises

1. A **fashion website** that sells accessories such as sunglasses captures images of users’ faces using the webcam and detects facial landmark points using a deep neural network running on TensorFlow.js. The **detected landmarks** are then used to synthesize an image of **the sunglasses overlaid on the user’s face** to simulate a try-on experience in the web page.
   - The experience is realistic because the simulated try-on can run with low latency and at a high frame rate thanks to client-side inference.
   - The user’s data privacy is respected because the captured facial image never leaves the browser.
2. A **mobile sports app** written in **React Native** (a cross-platform JavaScript library for creating native mobile apps) tracks users’ exercise. Using the HTML5 API, the app accesses real-time data from the phone’s gyroscope and accelerometer.
   - The data is run through a TensorFlow.js-powered model that **automatically detects the user’s current activity** type (for example, resting versus walking versus jogging versus sprinting.
3. A **browser extension** automatically detects whether the **person using the device is a child or an adult** (by using images captured from the webcam at a frame rate of once per 5 seconds and a computer-vision model powered by TensorFlow.js) and uses the information to block or grant access to certain websites accordingly.
4. A **browser-based programming environment** uses a recurrent neural network implemented with TensorFlow.js to **detect typos in code comments**.
5. A **Node.js-based server-side application** that **coordinates a cargo logistics service** uses real-time signals such as carrier status, cargo type and quantity, date/time, and traffic information to predict the estimated time of arrival (ETA) for each transaction. The training and inference pipelines are all written in Node.js, using TensorFlow.js, simplifying the server stack.

---

## **Vocabulary**

- **Machine learning** - a subfield of AI in which rules for performing a task such as image classification are discovered automatically by learning from examples in the training data.
- **Deep Learning** - refers to the rapid progress made in _speed_ and _techniques_ of **deep-neural networks** that started around 2012.
- **AI** - AI is the study of automating cognitive tasks. Machine learning is a subfield of AI in which rules for performing a task such as image classification are discovered automatically by learning from examples in the training data.
- **TensorFlow.js** - TensorFlow.js, the focus of this book, is a comprehensive, versatile, and powerful open source library for deep learning in JavaScript.
- **deep neural networks** - Deep learning is a class of machine learning algorithms that uses multiple layers to progressively extract higher-level features from the raw input.
  - For example, in image processing, lower layers may identify edges, while higher layers may identify the concepts relevant to a human such as digits or letters or faces.
- **range of problems** -
- **improve solution accuracy** - Accuracy is one metric for evaluating classification models. Informally, accuracy is the fraction of predictions our model got right.
  - Formally, accuracy has the following definition: Accuracy = Number of correct predictions Total number of predictions.
- **MNIST** - You define a model by multiplying the feature matrix with the weight and add a bias to it, then running it through a softmax function. y = tf.
- **MobileNet** - MobileNet is a streamlined architecture that uses depthwise separable convolutions to construct lightweight deep convolutional neural networks and provides an efficient model for mobile and embedded vision applications [15]. The structure of MobileNet is based on depthwise separable filters.
- **inference** -
- **transfer learning** -
- **neural networks** -
- **convnets** -
- **ResNet** -
- **Inception** -
- **ImageNet classification** -
- **machine translation** -
- **LSTM** -
- **models** -
- **mechanisms** -
- **GANs** -
- **training data** -
- **autoencoders** -
- **RNNs** -
- **sounds** -
- **generate text** -
- **image recognition** -
- **deep reinforcement** -
- **detection** -
- **javascript** -
- **Node.js** -

---

from [[_part-1-basic-concepts]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[_part-1-basic-concepts]: ../_part-1-basic-concepts.md "🌱 Part 1 Basic concepts"
[//end]: # "Autogenerated link references"
