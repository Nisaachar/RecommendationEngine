---

# Movie Recommendation System

## Overview
This project implements a comprehensive movie recommendation system utilizing various techniques such as knowledge-based, collaborative filtering, content-based, and model-based approaches. The system is designed to provide personalized movie recommendations to users based on their preferences and historical interactions with movies.

## Features
- **Data Pipeline:** Extracts movie data from the Movietweeting dataset hosted on GitHub, preprocesses it, and stores it in an SQLite database for efficient retrieval.
- **Knowledge-Based Recommendation:** Recommends movies based on statistical analysis of user ratings and movie metadata such as genre and release year.
- **Collaborative-Based Recommendation:** Utilizes user-movie interaction data to recommend movies based on similar users' preferences.
- **Content-Based Recommendation:** Recommends movies similar to those already liked by a user, based on content features such as genre and keywords.
- **Model-Based Recommendation:** Implements machine learning-based recommendation using the FunkSVD algorithm to predict user ratings for unseen movies.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/your_username/movie-recommendation-system.git
   ```

   
## Usage
1. Run the data pipeline script to extract, preprocess, and store movie data:
   ```
   python data_pipeline.py
   ```
2. Explore different recommendation techniques by running the respective scripts:
   - Knowledge-Based Recommendation:
     ```
     python knowledge_based_recommendation.py
     ```
   - Collaborative-Based Recommendation:
     ```
     python collaborative_based_recommendation.py
     ```
   - Content-Based Recommendation:
     ```
     python content_based_recommendation.py
     ```
   - Model-Based Recommendation:
     ```
     python model_based_recommendation.py
     ```

## Data
The Movietweeting dataset is used for this project, which provides detailed information about movies, user ratings, and reviews. The dataset is publicly available and can be accessed via the GitHub API.


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## Acknowledgements
- The Movietweeting dataset is provided by GroupLens Research (grouplens.org).
- Udacity - I learned a lot about data science using the course


## Contact
For any questions or feedback, please contact [thhat.guy.is@gmail.com](mailto:thhat.guy.is@gmail.com).

---
