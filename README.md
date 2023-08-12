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

Accuracy for Cifar10:

![df79fe94-3da4-4849-a628-456670e7845a](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/37af4659-fb92-4836-bfd0-a88b514b1a6a)

Accuracy for Fashion_Mnist:

![ee2c2a40-3c9c-4ac2-b90c-d3ceca5b1ace](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/89f95f8f-7767-4ea1-a296-4a880d7d906e)

Accuracy for Mnist:

![37b2db60-48a7-416c-9747-2bc86b5f8be0](https://github.com/K-Hooshanfar/Shallow_convolutional_NN_for_image_classification/assets/83825004/655018f1-6eca-4ffc-b9c9-72367c90fa68)




