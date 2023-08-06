# TensorFlow Dataset API
![img](https://lab.wallarm.com/wp-content/uploads/2018/06/TensorFlow-Dataset-API-1.png)

# Overview

In this lab, you start by refactoring the linear regression you implemented in the previous lab so that it takes data from a tf.data.Dataset, and you will learn how to implement stochastic gradient descent with it. In this case, the original dataset will be synthetic and read by the tf.data API directly from memory.

In the second part, you will learn how to load a dataset with the tf.data API when the dataset resides on disk.

# Learning objectives
In this lab, you will learn how to:

Use tf.data to read data from memory.

Use tf.data in a training loop.

Use tf.data to read data from disk.
