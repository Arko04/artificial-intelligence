# Artificial Intelligence

Coursework for **Artificial Intelligence** at the University of Tehran, Faculty of Electrical and Computer Engineering (Spring 2024). The course had a strong focus on machine learning and deep learning. All the work is in Jupyter notebooks (Google Colab) that mix derivations, explanations and TensorFlow/Keras or scikit-learn code, with outputs saved.

## Contents

| Work | Topics | Notebook |
|------|--------|----------|
| **Assignment 1** | Maths of SGD, Momentum, AdaGrad and RMSprop, compared in practice; **SMOTE** for imbalanced data, used with AdaGrad/RMSprop on the credit-card-fraud dataset | [assignment1.ipynb](assignment1-optimizers-and-smote/assignment1.ipynb) |
| **Assignment 2** | **KNN**, **SVM**, **Gradient Boosting** and **XGBoost**: theory and implementation on the Metro Interstate Traffic Volume dataset | [assignment2.ipynb](assignment2-knn-svm-boosting/assignment2.ipynb) |
| **HW3** *(team)* | Weight initialisation: **Glorot/Xavier** vs. **He/Kaiming** schemes with sigmoid, tanh, softsign, ReLU, Leaky ReLU and PReLU on CIFAR-10, reproducing the two original papers' experiments | [Q1](hw3-weight-initialization/q1-initialization-and-activations.ipynb) · [Q2](hw3-weight-initialization/q2-shallower-model.ipynb) |
| **Project 1** | **Transfer learning** with VGG16 and ResNet50 on a 3-class skin-disease image dataset, data augmentation, a **DCGAN** on CIFAR-10, and transfer-learning strategies for small datasets | [project1.ipynb](project1-transfer-learning-and-gan/project1.ipynb) |
| **Project 2** | **Clustering** (hierarchical with dendrograms, K-Means, DBSCAN), **decision trees** (Gini impurity vs. entropy), and **quantum computing** with Qiskit | [project2.ipynb](project2-clustering-trees-quantum/project2.ipynb) |
| **Project 3** | **Value and policy iteration**; **Deep Q-Networks** on CartPole (with Keras Tuner hyperparameter search) and FrozenLake; LSTM forward pass and BPTT by hand; **RNN / GRU / LSTM** forecasting on the Jena climate and S&P 500 series | [project3.ipynb](project3-reinforcement-learning-and-rnns/project3.ipynb) |

## Team

HW3 was done with **Mostafa Kermaninia** and **Ali Dehghan**. It's also published at [mostafa-kermaninia/Deep-learning-model-initialization-schemes](https://github.com/mostafa-kermaninia/Deep-learning-model-initialization-schemes). All the other work is individual.

## Running

The notebooks were written for Google Colab and read their datasets from Google Drive (`/content/drive/...`). To rerun one, upload the dataset to your Drive or change the path. The public datasets used are:

- [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) (Assignment 1)
- [Metro Interstate Traffic Volume](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume) (Assignment 2)
- CIFAR-10 (downloaded automatically by Keras)
- [Jena Climate 2009–2016](https://www.kaggle.com/datasets/mnassrib/jena-climate) (Project 3)
