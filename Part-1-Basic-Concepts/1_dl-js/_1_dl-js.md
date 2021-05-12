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

## Training in Browser steps

1. We can use sequential models to add layers
2. The first layer had to identify the input tensor shape
3. The last layer gives us the shape of the tensor output
4. We compile the model with direction on how it should learn
5. To train we call `fit` with input and expected output examples + some configuration

---

## **Vocabulary**

- <b>Machine learning</b>
  - a subfield of AI in which rules for **performing a task** such as image classification are discovered **automatically by learning from examples** in the training data.
- <b>Deep Learning</b>
  - refers to the rapid progress made in _speed_ and _techniques_ of **deep-neural networks** that started around 2012.
- <b>AI</b>
  - AI is the study of automating cognitive tasks. Machine learning is a subfield of AI in which rules for performing a task such as image classification are discovered automatically by learning from examples in the training data.
- <b>TensorFlow.js</b>
  - TensorFlow.js, the focus of this book, is a comprehensive, versatile, and powerful open source library for deep learning in JavaScript.
- <b>deep neural networks</b>
  - Deep learning is a class of machine learning algorithms that uses multiple layers to progressively extract higher-level features from the raw input.
  - For example, in image processing, lower layers may identify edges, while higher layers may identify the concepts relevant to a human such as digits or letters or faces.
- <b>range of problems</b>
- <b>improve solution accuracy</b>
  - Accuracy is one metric for evaluating classification models.
  - Informally, **accuracy is the fraction of predictions our model got right**.
  - Formally, accuracy has the following definition: Accuracy = Number of correct predictions Total number of predictions.
- <b>MNIST</b>
  - You define a model by multiplying the feature matrix with the weight and add a bias to it, then running it through a softmax function. `y = tf`.
- <b>MobileNet</b>
  - is a streamlined architecture that uses depth-wise separable convolutions to construct lightweight deep convolutional neural networks and provides an efficient model for mobile and embedded vision applications [15].
  - The structure of MobileNet is based on depth-wise separable filters.
- <b>inference</b>
- <b>transfer learning</b>
- <b>neural networks</b>
- <b>convnets</b>
- <b>ResNet</b>
- <b>Inception</b>
- <b>ImageNet classification</b>
- <b>machine translation</b>
- <b>LSTM</b>
- <b>models</b>
- <b>mechanisms</b>
- <b>GANs</b>
- <b>training data</b>
- <b>autoencoders</b>
- <b>RNNs</b>
- <b>sounds</b>
- <b>generate text</b>
- <b>image recognition</b>
- <b>deep reinforcement learning</b>
  - In reinforcement learning, the model has some input data and a reward depending on the output of the model. The model learns a policy that maximizes the reward. Reinforcement learning has been applied successfully to strategic games such as Go and even classic Atari video games.
- <b>detection</b>
- <b>javascript</b>
- <b>Node.js</b>
- <b>ensembles</b>
  - An ensemble is the combination of multiple models to create a single prediction. The key idea for making better predictions is that the models should make different errors. That way the errors of one model will be compensated by the right guesses of the other models and thus the score of the ensemble will be higher.

<link rel="stylesheet" type="text/css" media="all" href="../../../assets/css/custom.css" />

---

from [[_part-1-basic-concepts]]

[//begin]: # "Autogenerated link references for markdown compatibility"
[_part-1-basic-concepts]: ../_part-1-basic-concepts.md "🌱 Part 1 Basic concepts"
[//end]: # "Autogenerated link references"
