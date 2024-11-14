Music Genre Classification with PCA 🎶

This project focuses on classifying music into different genres using a technique called Principal Component Analysis (PCA). By reducing the complexity of our data with PCA, we can build a more efficient model for genre prediction.


---

Project Overview

Music genre classification is a popular problem in machine learning, where we aim to predict the genre of a song based on various musical features. This project helps to understand the relationship between these features and the genres they represent. We use PCA to simplify our data, which makes the model faster and can improve performance.

Dataset

The dataset used for this project is music_dataset_mod, which includes various features that represent musical aspects, such as tempo, pitch, rhythm, and more. Each entry in the dataset is labeled with its corresponding genre.

Steps

1. Data Preprocessing: Prepare the data by handling any missing values, scaling features, and encoding the genre labels for classification.


2. Principal Component Analysis (PCA):

PCA is used to reduce the dimensionality of the dataset.

It helps simplify the data by keeping only the most important features, making the model faster and less complex.



3. Classification Model:

After applying PCA, we train a classification model (like K-Nearest Neighbors, SVM, or any other classifier).

This model learns to associate the reduced features with specific music genres.



4. Model Evaluation: Evaluate the model’s accuracy to see how well it can predict genres in new, unseen data.


Dependencies

To run this project, you’ll need the following libraries:

Pandas: For data manipulation

NumPy: For numerical computations

Scikit-Learn: For PCA and classification algorithms

Matplotlib / Seaborn: For data visualization


Project Highlights

Data Simplification: We used PCA to reduce the dataset's complexity.

Effective Classification: Built a model that efficiently classifies genres even with reduced data dimensions.

Data Visualization: Visualizations to understand the data distribution before and after PCA.





