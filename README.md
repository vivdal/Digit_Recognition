# Digit_Recognition
A machine learning project to recognize handwritten digits based on the MNIST dataset.

## Dataset
<img src ="images/img1.PNG">

## Part 1

This folder contains the custom implementation of regression, support vector machines, softmax, kernels and PCA. It contains functions created to code the following mathematical representations of the algorithms and compare the accuracy of each.The files in this folder are:
<ul>
  <li>linear_regression.py: implemented in closed form using a regularizing parameter(test error: 0.77 with lambda = 0.01)</li>
  <img src ="images/reg.PNG">
  <li>SVM.py: implemented multiclass svm classification(test error: 0.08 with c=0.1)</li>
  <li> softmax.py: custom implementation of softmax with the following mathematical representation</li>
  <img src = "images/softmax.PNG">
  <img src = "images/costfunc.PNG ">
  <img src = "images/graddesc.PNG">
  <li>kernel.py : implements kernel in the following way</li>
  <li>features.py: implements PCA and cubic feature transformation </li>
  <li>test.py: contains test data for testing functions</li>
  
