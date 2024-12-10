# Movie_recommendation_101
Here's a detailed and organized **README** for your **Movie Recommender System** project:

---

# 🎬 **Movie Recommender System**

This project is a web-based **Movie Recommender System** that suggests similar movies based on user selection. It uses a **precomputed similarity matrix** and fetches movie posters via the **TMDb API** to provide a visually engaging experience.

---

## 🚀 **Project Overview**

The goal of this project is to help users discover movies similar to ones they already like. The system recommends movies based on features like **cast** and **crew** and displays their posters for an engaging user experience.

---

## 🔹 **Features**

- **Personalized Recommendations**: Suggests 5 movies similar to the selected movie.
- **Visual Display**: Fetches and shows movie posters using the TMDb API.
- **User-Friendly Interface**: Built with Streamlit for an easy-to-use web interface.
- **Fast Results**: Precomputed similarity matrix ensures quick recommendations.

---

## 🛠️ **Technologies Used**

- **Python**: Programming language for backend and data processing.
- **Streamlit**: For building the web interface.
- **Pickle**: For storing and loading preprocessed data and similarity matrices.
- **TMDb API**: For retrieving movie posters.
- **Requests**: For making HTTP requests to the TMDb API.
- **Machine Learning**: To calculate the similarity between movies based on their cast and crew.

---

## 📊 **Dataset**

The dataset includes the following columns:
- **`movie_id`**: Unique identifier for each movie.
- **`title`**: Name of the movie.
- **`cast`**: List of main actors in the movie.
- **`crew`**: List of directors and key crew members.

The data is preprocessed to generate a **similarity matrix**, which is used for finding similar movies.

---

## 🧩 **How It Works**

1. **Preprocessing**:
   - Features like cast and crew are combined and vectorized.
   - A **cosine similarity matrix** is computed to measure movie similarity.
   - The processed data and similarity matrix are saved using Pickle.

2. **Recommendation**:
   - The user selects a movie from the dropdown.
   - The system finds similar movies based on the similarity matrix.
   - Posters for the recommended movies are fetched using the TMDb API.

3. **Display**:
   - The interface shows the titles and posters of the top 5 recommended movies.

---



## 🖥️ **Project Structure**

```
movie-recommender-system/
│
├── model/
│   ├── movie_list.pkl       # Preprocessed movie data
│   └── similarity.pkl       # Precomputed similarity matrix
│
├── app.py                   # Streamlit app code
│
└── README.md                # Project documentation
```

---



---

## 📌 **Future Enhancements**

- Add more features like **genres** or **movie descriptions** for better recommendations.
- Incorporate **user ratings** to personalize suggestions further.
- Deploy the app on cloud platforms like **Render** or **Heroku** for wider accessibility.


---

## 📞 **Contact**

For any queries, reach out to:

- **Email**: [rsowmiya0711@gmail.com](mailto:rsowmiya0711@gmail.com)

---

Happy recommending! 🎥🍿
