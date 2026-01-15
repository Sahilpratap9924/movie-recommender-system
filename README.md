🎬 Movie Recommender System

A content-based movie recommendation system built using Python, Machine Learning, and Streamlit.
The app recommends movies similar to the one selected by the user and displays their posters using the TMDB API.

🔗 Live App:
👉 https://movie-recommender-system9924.streamlit.app/

🚀 Features

🔍 Search and select a movie

🎯 Get top 5 similar movie recommendations

🖼️ Movie posters fetched dynamically using TMDB API

⚡ Fast recommendations using cosine similarity

☁️ Deployed for free on Streamlit Community Cloud

🛠️ Tech Stack

Python

Streamlit

Pandas

NumPy

Scikit-learn

TMDB API

Hugging Face (for model storage)

🧠 How It Works

Movie data is vectorized using text features

Cosine similarity is calculated between movies

A precomputed similarity matrix is used for fast lookup

On selecting a movie, the top 5 most similar movies are recommended

📂 Project Structure
movie-recommender-system/
│
├── app.py                # Streamlit application
├── movie_dict.pkl        # Movie metadata (≤ 100MB)
├── requirements.txt      # Project dependencies
├── .gitignore            # Ignored large files
└── README.md             # Project documentation


⚠️ Note:
similarity.pkl is intentionally not stored on GitHub due to size limits.
It is downloaded securely from Hugging Face at runtime.

▶️ Run Locally

Follow these steps to run the project on your machine:

git clone https://github.com/Sahilpratap9924/movie-recommender-system.git
cd movie-recommender-system
pip install -r requirements.txt
streamlit run app.py

🌐 Deployment

The application is deployed using Streamlit Community Cloud (free, no credit card required).

Large model files are hosted on Hugging Face and loaded dynamically when the app starts.

🔐 API Key Note

This project uses the TMDB API to fetch movie posters.
For production, it is recommended to store the API key securely using Streamlit Secrets.

📌 Future Improvements

Add genre-based filtering

Improve UI with better layouts

Optimize memory for large similarity matrices

Add user-based recommendations

Secure API keys using environment variables

👨‍💻 Author

Sahil Pratap Singh
B.Tech – Electronics & Communication Engineering
Interest areas: Machine Learning, Web Development, Recommendation Systems

⭐ If you like this project, don’t forget to star the repository!
