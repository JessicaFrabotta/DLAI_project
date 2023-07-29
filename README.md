# Experimental Exploration of the Power of Group Equivariant Convolutional Networks
Equivariant neural networks are part of the broader topic of geometric deep learning, which is learning with data that has some underlying geometric relationships. Equivariance and symmetries in deep learning are important because they enhance robustness, reduce model complexity, improve data efficiency, aid interpretability, and ultimately lead to better performance.

In this project, I aim to replicate the methodology and experiments presented in the paper ["Group Equivariant Convolutional Networks"](https://arxiv.org/abs/1602.07576") by Cohen and Welling and extend it to new applications, particularly focusing on evaluating its effectiveness in enhancing robustness against adversarial attacks.

The project consists of the following sections:

1. Setup
2. Group Theory and Group Equivariant Convolution
3. Experiments on Rotated MNIST
4. Experiments on CIFAR-10
5. Experiments on Plant Leaves
6. Conclusions

The experiments in sections 2 and 3 are based on the work presented in the paper ["Group Equivariant Convolutional Networks](https://arxiv.org/abs/1602.07576") by Cohen and Welling. In section 4, Group Equivariant CNNs will be trained and tested on a novel dataset, which includes some classes from the healthy classes of [PlantVillage](https://data.mendeley.com/datasets/tywbtsjrjv/1), the most popular dataset for plant diseases classification. The other classes were collected by me and are part of my dataset published on [Kaggle](https://www.kaggle.com/datasets/jessicafrabotta/plant-diseases-dataset-with-augmentation). Additionally will be performed tests on perturbed examples.
