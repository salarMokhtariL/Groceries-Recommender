# Groceries Recommender System
## Scalable Recommender System Development with PyTorch and Pandas for Enhanced Personalization

> By $Helya$ $Hosseini$ $Nami$ & $Salar$ $Mokhtari$ $Laleh$

![Pink and Peach Technology LinkedIn Banner (3)](https://github.com/salarMokhtariL/salarMokhtariL/assets/75142232/0a2891df-3ecf-4702-9cbc-f57f55286884)



# Introduction
This notebook provides an implementation of a recommender system using PyTorch and demonstrates how to train and evaluate the model on a dataset of grocery transactions. The system utilizes item embeddings to represent the items in the dataset and computes their similarity to make recommendations.

# Dataset
The dataset used in this notebook is a list of grocery transactions. Each transaction consists of a list of items purchased by a customer. The dataset is available at the following URL:

https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/groceries.csv

# Implementation
The implementation consists of the following steps:

Load the dataset using pandas and convert it to a list of lists.
Create a dictionary to map each item to a unique integer.
Convert the dataset to a list of lists of integers using the mapping dictionary.
Convert the dataset to a PyTorch tensor.
Define the model architecture using PyTorch.
Train the model on the dataset using PyTorch.
Compute the item embeddings and similarity matrix.
Generate recommendations for each item using the similarity matrix.
