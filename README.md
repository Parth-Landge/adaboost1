
#K-Means Clustering from Scratch (Python)

This project contains a from-scratch implementation of the K-Means clustering algorithm using only NumPy, without relying on sklearn’s KMeans.

What this project demonstrates

Understanding of how K-Means works internally

Manual implementation of:

Random centroid initialization

Cluster assignment using Euclidean distance

Centroid update using mean of assigned points

Iterative convergence checking

Visualization of clustered data using Matplotlib

Files

temp.py – Custom implementation of the K-Means algorithm

ada-scratch.py – Script to generate data, run K-Means, and visualize clusters

Dataset

Synthetic 2D data is generated using make_blobs for testing and visualization.
The implementation can also be applied to real-world datasets (e.g., experience vs salary) after proper feature scaling.

Important Notes

Feature scaling is important for real datasets where features have different ranges.

Convergence is checked using numerical tolerance (np.allclose) instead of exact equality.

This project is intended for learning and demonstration purposes, not production use.

Technologies Used

Python

NumPy

matplotlib
