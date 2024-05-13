# Music-Recommendation-System

## Project Overview
This project aims to develop a personalized music recommendation system using various machine learning algorithms. The system recommends music to users based on features such as genre, year, tempo, and more. This project was carried out by Sai Sahithi Bethapudi at the Department of Applied Data Science, San Jose State University, under the guidance of Dr. Linsey Pang.
Music recommendation systems have become integral to digital music platforms, enhancing user experience by providing personalized music suggestions. This project explores content-based filtering techniques and evaluates multiple machine learning models to build an efficient recommendation system.

## Datasets
The datasets used in this project are obtained from the Spotify Web API using the SpotiPy library. The main datasets include:
	•	Songs Data: Contains song details such as song name, artist, release date, and genre.
	•	Audio Features Data: Contains audio features for each song such as tempo, danceability, and energy.

## Preprocessing
The data preprocessing involves cleaning, normalizing, and feature engineering. Steps include:
	•	Removing duplicates and null values.
	•	Converting song duration from milliseconds to minutes.
	•	Extracting features from text data using TF-IDF.
	•	Scaling numerical features using MinMaxScaler.
	•	Encoding categorical variables.
 
## Data Cleaning
The cleaning process involves:
	•	Dropping unnecessary columns such as preview_url, song_link, and artist_id.
	•	Handling missing values by dropping rows with null values.
	•	Ensuring no duplicate entries are present.
 
## Feature Engineering
Features were engineered to enhance the dataset:
	•	Extracting year from release_date and calculating the age of the song.
	•	Converting categorical variables into numerical values using encoding techniques.
	•	Applying TF-IDF vectorization on text features like song_name and artist_name.
 
 ## Machine Learning Models
Several machine learning algorithms are used to develop the recommendation system:
	•	Logistic Regression: For binary and multiclass classification.
	•	K-Nearest Neighbors (K-NN): For recommending songs based on similar genres.
	•	Decision Tree Classifier: For feature selection and classification.
	•	Random Forest Classifier: For ensemble learning and improving prediction accuracy.
	•	TF-IDF: For text analysis and feature extraction from song and artist names.
