# Shallow_convolutional_NN_for_image_classification


This repository contains implementation of "Shallow convolutional neural network for image classification". You can find the article here:[springer](https://link.springer.com/article/10.1007/s42452-019-1903-4)

The paper presents a solution to the challenges posed by complex deep CNNs in computer vision tasks. The paper introduces the Shallow Convolutional Neural Network (SCNNB).
The SCNNB offers an efficient alternative, utilizing batch normalization for quicker training convergence and accuracy improvement. With only four layers featuring small convolutional kernels, the SCNNB maintains performance while significantly reducing complexity. Experimental results demonstrate its ability to quickly learn data features, achieving 93.69% accuracy on fashion-MNIST and 99.42% accuracy on MNIST.

Architecture structure for our SCNNB model:

![Architecture structure for SCNNB model](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/b51a6f98-0992-40b7-a484-0d04c0f9489a)

# Results

| Our models | Mnist  | Cifar10 | Fashion_Mnist |
|----------|----------|----------|----------|
| Sscnnb   | 99.42%   | 77.49%   | 93.69%   |
| Scnnb_a  | 99.41%   | 74.02%   | 93.24%   |
| Scnnb_b  | 99.43%  | 74.74%  | 93.5%  |

Accuracy on Test set for Cifar10:

![b7803a82-f36a-4d9f-a2ae-cab4add20483](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/f504a45d-cb12-44d1-8341-541c1f72faa8)


Accuracy on Test set for Fashion_Mnist:

![66b40653-f092-4f64-83e5-2830ea9a11c9](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/4fc5d9e7-1ed6-423b-bb30-d04d1e6ccda9)

Accuracy on Test set for Mnist:

![9759b394-6db5-455b-a1dc-85c746490acf](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/70760d8f-091e-40d1-96bd-761be85004ab)





