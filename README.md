# Music Recommendation System

## Project Overview
In today’s digital world, music recommendation systems have become like the user’s musical sidekick, changing the way users explore vast libraries of tunes. This paper dives into the many reasons why these systems matter, shining a light on how they make one’s music experiences more personal, helping the users discover new tracks, and ensure they’re happy music enthusiasts. The music recommendation can be used to analyze the genres people listen to, the trends of music over a period of time and mainly recommend different songs to the users for them to continue staying on that particular application. The data gathered is first cleaned and an exploratory data analysis is performed on this. To build the recommendation system, we will use different content-based filtering techniques like K-Nearest Neighbors, Decision Tree Classifier, Random Forest Classifier, Logistic Regression and TF-IDF. Taking different features into account like the genre, year, beat, these models help recommend music to the users. Metrics including recommendation accuracy, diversity, and user input will be used to determine the system’s efficiency. The music recommendation system can be used to enhance the experience of listeners by recommending songs that fit their tastes based on similar songs. It will boost the user engagement as it personalizes the listening experience by creating a dynamic and entertaining music discovery journey for the users. This subsequently leads to the discovery of a variety of artists, songs and even languages according to the user’s preferences.

## Datasets
The datasets used in this project are obtained from the Spotify Web API using the SpotiPy library. The main datasets include:
- Songs Data: Contains song details such as song name, artist, release date, and genre.
- Audio Features Data: Contains audio features for each song such as tempo, danceability, and energy.

## Preprocessing
The data preprocessing involves cleaning, normalizing, and feature engineering. Steps include:
- Removing duplicates and null values.
- Converting song duration from milliseconds to minutes.
- Extracting features from text data using TF-IDF.
- Scaling numerical features using MinMaxScaler.
- Encoding categorical variables.
 
## Data Cleaning
The cleaning process involves:
- Dropping unnecessary columns such as preview_url, song_link, and artist_id.
- Handling missing values by dropping rows with null values.
- Ensuring no duplicate entries are present.
 
## Feature Engineering
Features were engineered to enhance the dataset:
- Extracting year from release_date and calculating the age of the song.
- Converting categorical variables into numerical values using encoding techniques.
- Applying TF-IDF vectorization on text features like song_name and artist_name.
 
 ## Machine Learning Models
Several machine learning algorithms are used to develop the recommendation system:
- Logistic Regression: For binary and multiclass classification.
- K-Nearest Neighbors (K-NN): For recommending songs based on similar genres.
- Decision Tree Classifier: For feature selection and classification.
- Random Forest Classifier: For ensemble learning and improving prediction accuracy.
- TF-IDF: For text analysis and feature extraction from song and artist names.
