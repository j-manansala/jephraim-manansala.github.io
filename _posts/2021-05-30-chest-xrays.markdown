---
layout: post
title:  "Detecting Medical Conditions on Chest Radiographs"
categories: deep_learning classifier
list_title: "Deep Learning"
---
by: [Jephraim Manansala](https://www.linkedin.com/in/jephraim-manansala/), [Misha Hwang](https://www.linkedin.com/in/mishaysabelhwang/),  [Karl Navarro](https://www.linkedin.com/in/karl-ludwig-navarro/), [Lennart Panton](https://www.linkedin.com/in/lennartpanton/)

Asian Institute of Management

With the pandemic happening, public health-care workers in specialized fields have to perform their usual medical tasks continuously while performing COVID-19 tasks. Hospitals are also facing a shortage of health-care workers. Thus, the workload and shortage are cuasing extreme stress and burnout for these public health-care workers. While being in the frontlines, radiologists still face the tedious process of diagnosing chest-xray, potential diagnosis conflicts with other radiologists, and too many human errors involved. Thus, our team proposes to use big data and artificial neural networks to detect medical conditions in chest radiographs.

We used 42GB of NIH Chest X-ray Dataset that contains 112,120 chest radiograph images, 15 different medical conditions, and 30,805 unique patients.The dataset was uploaded into the Amazon Web Service S3 bucket to be efficiently computed with an EC2 instance type C4.2xlarge.The uploaded images were vectorized using a pre-trained model called Xception. Afterwards, we explored the data and discovered that medical conditions were imbalanced. The condition "no findings" has around 60,000 instances which is the majority class. Moreover, sample data were printed for verification. Then the total number of each findings were obtained. Afterwards, oversampling and undersampling were done to address the data imbalance. A convolutional neural network model was then trained using the whole dataset. Overall, the model had an accuracy of 79%.

With a 79% accuracy in detecting medical conditions, radiologists can diagnose chest x-rays faster with the model. Note, the model is not intended to replace Radiologists. Based on the results of the model, we recommend to augment of the chest radiographs image dataset further, to consider other pre-trained models for improvement of the 79% accuracy and detection medical condition severity, and to explore multi-labeled outputs for multiple condition detection.

Keywords: Deep Learning, Chest Radiographs, Big Data

<i>Full text article and source codes can be provided upon request. </i>