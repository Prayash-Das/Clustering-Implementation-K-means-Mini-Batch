 # K-means and Mini-Batch K-means Implementation README

## Overview
This repository contains Python code implementing the K-means clustering algorithm and Mini-Batch K-means on both a 2D dataset and the MNIST dataset. The code showcases the process of clustering data points and evaluating the clustering models' performance.

## Files Included
- `kmeans_2d_mnist.ipynb`: Jupyter Notebook containing the implementation of K-means and Mini-Batch K-means algorithms on 2D and MNIST datasets.
- `README.md`: This README file providing a detailed overview of the repository and instructions for running the code.

## Steps to Run the Code
1. **Environment Setup:**
   - Ensure you have Python installed along with the required libraries such as NumPy, Matplotlib, TensorFlow, and scikit-learn.
2. **Open the Notebook:**
   - Open the `kmeans_2d_mnist.ipynb` notebook in Jupyter Notebook or any compatible environment.
3. **Execute Code Cells:**
   - Run each code cell sequentially to execute the K-means and Mini-Batch K-means implementations.
4. **View Results:**
   - Explore the generated visualizations and output metrics to understand the clustering results.
5. **Additional Information:**
   - The code includes comments and explanations to aid understanding of each step.
   - Make sure to have the necessary packages installed and data accessible before running the code.

## Contents of `kmeans_2d_mnist.ipynb`
1. **Step 1: 2D Data Generation and Visualization**
   - Generates a 2D dataset with two categories and visualizes it using a scatter plot.

2. **Step 2: Helper Functions and Initialization**
   - Defines helper functions for Euclidean distance and initializes centroids for K-means.

3. **Step 3: K-means Implementation**
   - Implements the K-means algorithm including assigning clusters and updating centroids.

4. **Step 4: Training K-Means on MNIST Dataset**
   - Loads the MNIST dataset, flattens the images, and trains a K-means model.

5. **Step 5: Mini-Batch K-means**
   - Trains Mini-Batch K-means models with different cluster numbers and evaluates the best model on the test dataset.

## Results and Evaluation
- Visualizations: Provides visual representations of clustering results for both 2D and MNIST datasets.
- Metrics: Computes and displays performance metrics such as training time and inertia values.

## Additional Information
- Author: Prayash Das
- Contact: pdas4@stevens.edu
- For any questions or issues, please reach out to the author.
