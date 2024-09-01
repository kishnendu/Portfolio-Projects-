# Netflix-Recommendation-System

## Introduction:

Welcome to the Netflix Recommendation System project! This project aims to develop a recommendation system for Netflix users based on their viewing history and preferences. By leveraging machine learning algorithm SVD and data analysis techniques, I strive to deliver personalized recommendations to enhance the user experience on the platform.


## Objectives
1. Find out the list of most popular and liked genre
2. Create Model that finds the best suited Movie for one user in every genre.
3. Find what Genre Movies have received the best and worst ratings based on User Rating.

## Algorithm Information
### Singular Value Decomposition (SVD)

SVD is a mathematical technique used in linear algebra and numerical analysis. It decomposes a matrix A into three matrices: U, Σ, and V^T. In the context of collaborative filtering for recommendation systems, the user-item interaction matrix is decomposed using SVD. The resulting matrices U, Σ, and V^T are employed to make recommendations for missing values in the original matrix.

### Power Iteration

Power iteration is an iterative method to find the dominant eigenvalue and corresponding eigenvector of a matrix. In the context of SVD, power iteration is used to find singular vectors and values. The algorithm converges to the dominant singular vector and value by updating vectors at each iteration.

### Deflation

Deflation is a technique used in SVD to iteratively find subsequent singular vectors and values. It involves subtracting the contributions of already computed singular vectors and values from the original matrix. This process helps in finding a series of singular vectors and values that approximate the original matrix.

### Truncation Parameter (k)

The parameter k in SVD represents the number of singular values and their corresponding vectors to retain during truncation. It determines the dimensionality of the approximation to the original matrix. The choice of k is a trade-off between dimensionality reduction and preserving information.


## Dataset Information
The dataset contains the following columns:

1) ID: Contains separate keys for customers and movies.
2) Rating: Represents user ratings for all movies.
3) Genre: Highlights the category of the movie.
4) Movie Name: Name of the movie corresponding to the movie ID.



To get started with the Netflix Recommendation Engine project, I followed these steps:

1) Download the Dataset: Obtain the Netflix dataset containing customer ratings and movie information.
2) Data Preprocessing: Clean and preprocess the dataset, handling missing values and encoding categorical variables if necessary.
3) Exploratory Data Analysis (EDA): Perform exploratory data analysis to gain insights into the dataset, understand user preferences, and identify patterns.
4) Model Development: Implement recommendation algorithms such as collaborative filtering, content-based filtering, or hybrid approaches using machine learning libraries like scikit-learn.
5) Model Evaluation: Evaluate the performance of the recommendation models using appropriate evaluation metrics and techniques.


## Acknowledgements
The training data came in 17,000+ files. In the interest of keeping files together and file sizes as low as possible, I used one combined file: combined_data_1.txt

The contest was originally hosted at http://netflixprize.com/index.html

The dataset was downloaded from https://archive.org/download/nf_prize_dataset.tar


## References: 
This project utilized information and resources from various internet sources. The following references were instrumental in the development of this project:

1) Kaggle: The Netflix dataset used in this project was obtained from Kaggle, a platform for data science competitions and datasets.
2) Stack Overflow: Community discussions and solutions on Stack Overflow were referenced to address specific programming challenges encountered during the project development.
3) GitHub: Open-source repositories on GitHub served as a reference for best practices, code snippets, and implementation examples related to recommendation engines and machine learning.

![image](https://github.com/DrPoojaAbhijith/Netflix-Recommendation-Engine/assets/160575120/9b50a2ee-e97a-456c-ba0c-be34fd3da330)
