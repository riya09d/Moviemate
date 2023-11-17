# Moviemate
**Moviemate: Interactive Movie Recommender System**

Moviemate is a Python-based movie recommender system developed using the Streamlit framework. This application provides users with personalized movie recommendations based on their preferences, enhancing the overall movie discovery experience.

**Key Features:**

1. **Real-Time Movie Posters:**
   - Utilizes The Movie Database (TMDb) API to fetch real-time movie posters.
   - Enriches the user experience by providing comprehensive movie details and visually appealing posters.

2. **Advanced Collaborative Filtering:**
   - Implements advanced collaborative filtering techniques for accurate movie recommendations.
   - Utilizes similarity calculations in the algorithm to suggest 5 similar movies based on user preferences.

3. **User-Friendly Interface:**
   - Designed with Streamlit to ensure an intuitive and user-friendly interface.
   - Facilitates easy exploration of movie recommendations, enhancing user engagement.

**How It Works:**
   - Users can select a movie of interest from the provided list.
   - Upon clicking the "Recommend" button, the system employs collaborative filtering to identify and suggest 5 similar movies.
   - Real-time movie posters from TMDb API enhance the visual aspect of the recommendations.

**Getting Started:**
   - Clone the repository to your local machine.
   - Install the required Python packages listed in the `requirements.txt` file.
   - Run the Streamlit app using the command `streamlit run your_app_name.py`.

**Dependencies:**
   - Streamlit: for creating interactive web applications.
   - Pandas: for efficient data manipulation and analysis.
   - Requests: for handling HTTP requests to fetch movie data from TMDb API.
   - Pickle: for serializing and deserializing Python objects.

**Note:** Ensure you have the necessary API key for TMDb, and update it in the code for seamless integration.

**Contributions:**
   - Contributions and feedback are welcome! Feel free to open issues or pull requests.

**Acknowledgments:**
   - Special thanks to TMDb for providing the API that enriches our movie recommendations with real-time data.

Explore and enjoy personalized movie recommendations with Moviemate!
