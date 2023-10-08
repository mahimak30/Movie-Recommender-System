# Project Title: Content-Based Movie Recommender System

### Author: Mahima Kakumanu

In this project, I created a content-based movie recommender system using Python and various machine learning and natural language processing techniques. The project involved the following key topics:

## 1. Data Preprocessing:

I began by loading and inspecting two datasets, 'tmdb_5000_movies.csv' and 'tmdb_5000_credits.csv', using the Pandas library. These datasets contained information about movies, including their titles, genres, keywords, cast, crew, and more.


## 2. Data Integration:

I merged the two datasets based on movie titles to create a consolidated dataset that included all relevant movie information.

## 3. Text Data Processing:

To prepare the textual data for analysis, I performed text cleaning and transformation. This involved parsing JSON-like columns, extracting relevant information, and converting text to lowercase.

## 4. Text Vectorization:

To enable machine learning, I used Count Vectorization to convert the movie descriptions and associated tags into numerical format. This step allowed me to represent movies as vectors of features.

## 5. Cosine Similarity:

Using cosine similarity, I calculated the similarity between movies based on their feature vectors. This similarity metric helped identify movies with similar content.

## 6. Recommender System:

Finally, I implemented a recommender system that takes a movie title as input and suggests a list of similar movies based on content similarity. The system uses the cosine similarity scores to rank and recommend movies.

## What I Learned:

Through this project, I gained practical experience in data preprocessing, text data cleaning, and text vectorization.
- I learned how to use natural language processing techniques to transform text data into a format suitable for machine learning.
- I developed a deeper understanding of cosine similarity as a measure of content similarity.
- This project also enhanced my skills in data analysis, Python programming, and machine learning model implementation.
In summary, this content-based movie recommender system project allowed me to apply various data science concepts to real-world data and build a functional recommendation system. It serves as a great example of leveraging data and text processing techniques to provide valuable recommendations to users based on their movie preferences.
