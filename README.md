# Book Recommendation System

A scalable and efficient book recommendation system built using machine learning techniques like clustering and dimensionality reduction. The system is designed to suggest books based on similarities in genre, author, and rating features.

## Overview

This project processes and analyzes book data from Goodreads to recommend similar books. It includes:

* Data cleaning and preprocessing
* Feature encoding and transformation
* Dimensionality reduction using PCA
* Clustering with KMeans
* Recommendation generation based on cluster membership

## Features

* **Data Cleaning**:

  * Handles missing values
  * Converts data types appropriately for processing

* **Feature Engineering**:

  * Encodes authors using OneHotEncoder
  * Uses MultiLabelBinarizer for genre encoding
  * Normalizes numerical features (ratings, etc.)

* **Dimensionality Reduction**:

  * Reduces the feature space using Principal Component Analysis (PCA) for efficient clustering

* **Clustering**:

  * Groups similar books using KMeans
  * Determines optimal cluster count using the Elbow Method

* **Recommendation Generation**:

  * Recommends books based on shared cluster membership

## Dataset

The dataset includes the following features:

* Titles
* Authors
* Genres
* Average ratings
* Number of ratings
* Reference URLs

##  Tech Stack / Dependencies

* Python 3
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

##  Usage

1. **Load Dataset**

   * Import and inspect the dataset.

2. **Clean and Prepare Data**

   * Handle missing values and convert relevant columns.

3. **Feature Engineering**

   * Encode authors and genres, normalize ratings.

4. **Apply PCA**

   * Reduce dimensionality of the feature matrix.

5. **Cluster Books**

   * Run KMeans to group similar books.

6. **Generate Recommendations**

   * Suggest books based on cluster similarity.

##  Results

The model effectively clusters books into meaningful groups based on content and metadata, enabling useful and interpretable recommendations.

##  Future Improvements

* Add collaborative filtering to incorporate user-based recommendations
* Integrate with a web interface for interactive use
* Include more metadata like user reviews and publication years


