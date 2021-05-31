---
layout: post
title:  "Detecting Electricity Theft using Neural Networks"
categories: deep_learning classifier
list_title: Highlighted
date:   2021-05-30 
---
by: [Jephraim Manansala](https://www.linkedin.com/in/jephraim-manansala/), [Misha Hwang](https://www.linkedin.com/in/mishaysabelhwang/),  [Karl Navarro](https://www.linkedin.com/in/karl-ludwig-navarro/), [Lennart Panton](https://www.linkedin.com/in/lennartpanton/)

Asian Institute of Management

Electricity theft is the illegal act of acquiring electricity without authorization. This act may include but is not limited to bypassing the electricity meter, tampering with meter reading, hacking the meter, or tampering with electrical wire. Moreover, it is one of the primary contributors to non-technical system losses. Both consumers and utility companies are affected by these for many reasons. On the one hand, consumers may be paying for electricity theft under the system loss charges, capped at 8.5% of electricity usage. On the other hand, utility companies have to spend labor cost, time, and effort to track down electricity theft. Thus, our team proposes to develop a convolutional neural network in a parallel architecture to detect electricity theft with the daily average electricity consumption data. The exploratory data analysis revealed that the class "thief" and "non-thief" were highly imbalanced. As a result, the model used Generative Adversarial Networks (GANs) to address the data imbalance. Once the data is balanced, the time series data converted into a 2-dimensional calendar format array using different time groups (daily, weekly, biweekly, and monthly). Each time group was used to train a CNN model with varying inputs. The trained CNNs had high accuracies but low recall scores. A parallel CNN architecture was developed that captured the varying periodicities to address this problem. This model achieved an accuracy of 91.28% and a recall score of 63.64%. Hence, the model can detect electricity theft efficiently, but it can improve further to roll out a full prototype.

Keywords: Electricity Theft, Prediction, Deep Learning, Convolutional Neural Network

<i>Full text article and source codes can be provided upon request. </i>