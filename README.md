# Movie_Recommender_System

# Project Overview
This project is a content-based Movie Recommender System that suggests similar movies based on the user’s selection. The system uses cosine similarity between movie feature vectors to determine recommendations. The model is pre-trained, and the similarity matrix is stored using the Pickle module for efficient retrieval. The project is implemented using Streamlit for an interactive web interface.

# Features
- Provides movie recommendations based on a selected movie.
- Uses precomputed similarity scores stored in a serialized file (similarity.pkl).
- Interactive web-based interface using Streamlit.
- Fast and efficient retrieval of similar movies using Pandas.

# How It Works
1. The dataset containing movie information is preprocessed and converted into numerical feature vectors.
2. The cosine similarity between movies is computed and stored in a serialized format (similarity.pkl).
3. A user selects a movie from the dropdown menu in the Streamlit application.
4. The system retrieves and displays the top five most similar movies based on the similarity scores.

# Setup
1. Clone the repository.
2. Install the required dependencies using pip install -r requirements.txt.
3. Run the Streamlit application using streamlit run main.py.

# File Descriptions
- main.py: The main script that runs the Streamlit application and handles movie recommendations.
- movie_dict.pkl: A serialized dictionary containing movie data such as titles and metadata.
- similarity.pkl: A serialized similarity matrix that stores the precomputed similarity scores between movies.

# Technologies Used
- Python: Programming language used for implementation.
- Pandas: Used for handling and processing movie data.
- Streamlit: Used to create an interactive web-based interface.
- Pickle: Used to store the movie dataset and similarity matrix for quick retrieval.
