# Content-recommendation-system-on-Disney-hotstart

**Objective**

The Content Recommendation System aims to provide personalized and relevant content suggestions to users based on their viewing history, preferences, and behavior. This enhances user engagement, satisfaction, and retention by helping them discover content tailored to their interests while promoting content that increases platform revenue.

**Project Overview**

This project implements a content recommendation system using Python and machine learning techniques. The system leverages cosine similarity for item comparison, extracts meaningful content features, and applies recommendation algorithms like collaborative filtering and content-based filtering.

**Modules**

**1. Data Collection Module**

**Source:** Data was collected from Kaggle.

**Preprocessing:**

    Removed null values to ensure clean data.
    
    Renamed columns for better understanding and usability.

**2. Feature Extraction Module**

Extracted key features from the content metadata:

    Genre
    
    Language
    
    Duration
    
    Cast and Crew

**3. Recommendation Algorithm Module**

Applied cosine similarity to calculate the similarity between items.

**Algorithms used:**

    Content-Based Filtering: Recommends content similar to a user's previous choices.
    
    Collaborative Filtering: Recommends content based on user behavior.
    
    Hybrid Approach: Combines multiple techniques for improved accuracy.

**Algorithm: Cosine Similarity**

**Definition:** Cosine similarity measures the cosine of the angle between two vectors, producing a value between -1 (completely dissimilar) and 1 (perfectly similar).

**Formula:**

**Implementation:**

    Compute the dot product of two feature vectors.
    
    Normalize the result by dividing by the product of their magnitudes.

**Implementation**

**Language:** Python

**Libraries Used:**

    Pandas (Data Preprocessing)
    
    NumPy (Numerical Operations)
    
    Scikit-learn (Machine Learning Algorithms)
    
    Matplotlib/Seaborn (Data Visualization)

**Approach:**

    Collected and cleaned the dataset.
    
    Extracted relevant features.
    
    Implemented cosine similarity and other recommendation algorithms.

**Conclusion**

The Content Recommendation System for Disney+ Hotstar enhances user experience by providing accurate, personalized content suggestions. By combining techniques like content-based filtering, collaborative filtering, and cosine similarity, the system ensures relevant recommendations for each user.





