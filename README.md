# DeepfakeDetection


With the recent advancements in AI technology in-particularly General Adversarial1Networks, the creation of realistic fake media has become prevalent and easily2accessible.  In this paper we have explored a wide range of methods to detect3fake images.  We have analysed machine learning classification approaches as4using Decision tree, boosted trees as adaboost, gradientboost and SGDClassifier5coupled with image processing techniques to distinguish fake images from real.6We have also explored deep learning methods as attention-based Convolutional7Neural Network and encoding latent distribution using Autoencoder for learning8real and fake feature distribution. The paper discusses all the explored approaches9and their performance in detail.


The link to our dataset:https://www.kaggle.com/unkownhihi/deepfake/


Explored models and their performance comparison
Approach   Test accuracy    F1 

Baseline Inception 0.63    0.6

Stochastic gradient 0.57.  0.57

AdaBoost        0.57       0.56

GradientBoosting. 0.59.    0.61

FacialGradient CNN 0.95.   0.87

BiModal encoder learning0.930.85
