
# PCA 

## Overview
This repository contains three lab exercises focused on Principal Component Analysis (PCA). The objectives of these exercises are to understand the principles of PCA, apply it for image compression, and use it as a preprocessing step for feature reduction in a classification task. 

## Lab Exercises

### Lab Exercise 1: Understanding PCA with a Simple Dataset
**Objective:**  
To understand the basic principles of PCA by reducing the dimensionality of the Iris dataset.

**Instructions:**
1. **Load the Dataset:**  
   Utilize the Iris dataset, which consists of 4 features and 3 classes.

2. **Exploratory Data Analysis (EDA):**  
   Visualize the data to identify potential patterns and relationships among the features.

3. **Standardization:**  
   Standardize the features to have a mean of 0 and a standard deviation of 1.

4. **Covariance Matrix:**  
   Calculate the covariance matrix of the standardized data.

5. **Eigenvalues and Eigenvectors:**  
   Compute the eigenvalues and eigenvectors of the covariance matrix to identify the principal components.

6. **PCA Transformation:**  
   Sort the eigenvectors by the magnitude of their corresponding eigenvalues and project the data onto the first two principal components.

7. **Visualization:**  
   Create a scatter plot of the data in the new 2D space, using different colors for each class in the Iris dataset.

---

### Lab Exercise 2: PCA for Image Compression
**Objective:**  
To demonstrate the power of dimensionality reduction in data compression by using PCA to compress and reconstruct an image.

**Instructions:**
1. **Load an Image:**  
   Load a grayscale image (e.g., 256x256 pixels).

2. **Reshape the Image:**  
   Flatten the image to a 2D matrix where each row represents a pixel and each column corresponds to pixel intensity values.

3. **Apply PCA:**  
   Perform PCA on the image data, reducing the number of principal components used for reconstruction.

4. **Reconstruction:**  
   Reconstruct the image using varying numbers of principal components (e.g., 5, 20, 50, 100).

5. **Visualize Results:**  
   Display the original image alongside the reconstructed images at different levels of dimensionality reduction.

---

### Lab Exercise 3: PCA for Feature Reduction in a Classification Task
**Objective:**  
To apply PCA as a preprocessing step to reduce the feature space for a classification problem and assess its effect on model performance.

**Instructions:**
1. **Load a Dataset:**  
   Use a dataset with many features, such as the Wine dataset from sklearn.

2. **Split the Data:**  
   Divide the dataset into training (70%) and testing (30%) sets.

3. **Baseline Model (No PCA):**  
   Train a classification model (e.g., Logistic Regression or SVM) on the raw dataset and evaluate its performance using accuracy, precision, and recall.

4. **Apply PCA:**  
   Apply PCA to the training data while retaining various numbers of components (e.g., 2, 5, 10).

5. **Project Test Data:**  
   Project the test data onto the same principal components derived from the training data.

6. **Train and Evaluate:**  
   Train the same classification model on the reduced dataset and compare model performance with different numbers of principal components.

7. **Visualization:**  
   Plot a graph to show how accuracy changes as the number of components increases.

---


## Conclusion
These exercises provide practical insights into the application of PCA for dimensionality reduction, data compression, and its role in enhancing model performance in classification tasks.
