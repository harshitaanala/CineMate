# 🎬 Your one stop Movie Recommender System
A simple Movie Recommender System that suggests movies based on the similarity of content. This system uses content-based filtering, where recommendations are generated based on the characteristics of movies, such as genres, plot summaries, or keywords. The app is built with Streamlit for a user-friendly, interactive web-based interface.

## 📝 Features
- Content-Based Recommendations: Suggests movies based on similarity with selected movie content (genres, keywords, or plot descriptions).
- Search Functionality: Allows users to search for movies within the dataset.
- Interactive UI: Built with Streamlit to offer an easy-to-use interface where users can view recommendations instantly.
- Details of Recommendations: Each recommended movie includes basic information like title, genre, and overview.

## 🚀 How It Works
- Data Processing: Uses a dataset of movies with details like genres, plot summaries, and keywords.
- Content-Based Filtering: Calculates similarity between movies using a feature vector (e.g., genres, keywords, and plot descriptions).
- Cosine Similarity: Measures the similarity between feature vectors of movies to find the closest matches.
- Streamlit Interface: Displays the recommendations on an interactive web app where users can select or search for a movie and view recommendations.

## 📦 Tech Stack
- Python: Core programming language
- Streamlit: For building the web app UI
- Pandas: Data processing and manipulation
- Scikit-Learn: Cosine similarity calculation

## 📊 Usage
* Start the app: Run streamlit run app.py and open the URL provided in the terminal.
* Search for a movie: Use the search bar to select a movie.
* View Recommendations: Based on the selected movie, the app will display a list of similar movies.
