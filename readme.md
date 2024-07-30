# Movie Recommendation System

## Overview
This project implements a movie recommendation system using content-based filtering techniques. It analyzes movie attributes such as overviews, genres, keywords, cast, and crew to provide personalized movie suggestions to users.

## Features
- **Data Collection**: Utilizes data from the TMDB (The Movie Database) for comprehensive movie information.
- **Data Preprocessing**: Handles missing values, merges relevant features, and formats text data for analysis.
- **Feature Engineering**: Creates a 'tags' feature by combining movie overviews, genres, keywords, cast, and crew.
- **Text Vectorization**: Implements Bag of Words to convert text data into a numerical format suitable for machine learning.
- **Recommendation Algorithm**: Uses cosine similarity to compare movies and recommend titles based on user preferences.

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TMDB API (for data)

## Getting Started

### Prerequisites
Ensure you have Python 3.x installed on your machine. You will also need to install the required packages. You can do this using pip:

```bash
pip install pandas numpy nltk scikit-learn
```

## Data Preparation
1. Download the dataset files:

- tmdb_5000_movies.csv
- tmdb_5000_credits.csv

2. Place the CSV files in the project directory.

## Usage

- Input the title of a movie to receive recommendations based on similar content.
- The system will output a list of recommended movies.