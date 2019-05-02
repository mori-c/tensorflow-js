# Tensorflow
ML Introductory Practice Using Tensorflow


<br />
### Overview
* tf.js is 3-5x slower than GPU tf

<br />
<br />

## Setup

1. Clone [Ryan Marchildon's](https://github.com/RyanMarchildon/tfjs-torontoai-lecture) repo
```
$ git clone git@github.com:RyanMarchildon/tfjs-torontoai-lecture.git
```

2. Webserver

JS
```
$ npm install local-web-server -g
```

Python
```
$ python3 -m http.server
```
<br />
<br />

## Getting Started

1. Fundamental

tf.js /index.html
```
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.0.0/dist/tf.min.js"></script>
```

2. Tensors 
* multi-dimensional array vector

3. CNN, tfjs-vis

4. Memory management
   
5. MNIST data with tf.js
* lodd() and confusion matrices
* local host this model due to cross origin reference sharing 
* need to add script call below in html file
```
  <!-- Import TensorFlow.js -->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.0.0/dist/tf.min.js"></script>
  <!-- Import tfjs-vis -->
  <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-vis@1.0.2/dist/tfjs-vis.umd.min.js"></script>

  <!-- Import the data file -->
  <script src="data.js" type="module"></script>

  <!-- Import the main script file -->
  <script src="main.js" type="module"></script>
```

const xt = tf.tensor1d(xData); 


define loss / error()
- of predicted output to actual output
- checks parameter space, to min

create linear regression

stochastic descent


lodd() and confusion matrices


<br />
<br />
<br />
<br />
<br />
<br />

Here's Rangle.io's take on building AI applications with tensorflow.js

[![screencapture article ai rangle.io tensorflow.js](img/rangleio-article-thumb)](https://github.com/mori-c/tensorflow/blob/master/img/rangle-io-blog-bringing-artificial-intelligence-to-the-browser-with-tensorflow-js-2019-05-02-18_34_06.png)



