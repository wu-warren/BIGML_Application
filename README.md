# BIGML_Application

# Warren Wu

Coding Assignment: Implementing a Solution for the Spurious Correlations Problem

[Self-assessment for those interested in Empirical Work]. If this is too difficult for you, please consider taking more ML courses first.

We have a sample task just to help us understand if you're familiar with Pytorch etc. and how comfortable you are with machine learning in general.

Deep neural networks often exploit non-predictive features that are spuriously correlated with class labels, leading to poor performance on groups of examples without such features. Using the SpuCo Package (SpuCo Documentation), we'd like you to implement a simple method to remedy spurious correlations in SpuCoMNIST (use default parameters to initialize the dataset).

The method (George) we'd like you to implement has a 3 step pipeline:
1. Train a model using ERM *(I used lenet for performance)*
2. Cluster inputs based on the output they produce for ERM *(I used kmeans)*
3. Retrain using "Group-Balancing" to ensure in each batch each group appears equally.

We'd like you to send us a notebook with your code and outputs (similar to the SpuCo Quickstart Notebooks).

Upload your notebook (with both code and outputs) to a public GitHub repository and share the link here. 
