# MoviXpert - Your AI-Powered Movie Recommendation

Welcome to the TMDB Movie Recommendation System! This project aims to provide you with personalized movie recommendations based on your preferences and movie-watching history. Whether you're a cinephile looking for hidden gems or a casual moviegoer seeking entertainment, our recommendation system is here to help you discover new and exciting films.

## How it Works

The TMDB Movie Recommendation System leverages the power of collaborative filtering and machine learning to suggest movies that align with your interests. Collaborative filtering analyzes the behavior of multiple users and identifies patterns in their movie preferences. By understanding the tastes of users with similar interests, the system can predict which movies you might enjoy, even if you haven't seen them yet.

## Input Format

![MRS_input](https://github.com/Abhishek676062/Movie-Recommended-System/assets/81158782/f2f5e2c4-b774-47e3-aba4-365ad9512b16)

## Output Format

![MRS_output](https://github.com/Abhishek676062/Movie-Recommended-System/assets/81158782/7abb421e-e7b9-438f-89c4-3df647125276)


Our recommendation system comprises two main steps:

1. **Data Preprocessing**: The TMDB dataset, which contains a vast collection of movies, is subjected to thorough cleaning and preprocessing. This step involves handling missing values, removing duplicates, and extracting essential features that will be used to build the recommendation model.

2. **Model Building and Recommendation**: After preprocessing the data, we utilize collaborative filtering algorithms to train a powerful recommendation model. This model learns from the historical interactions between users and movies and identifies the hidden connections that lead to successful recommendations.

## Requirements

Before you can enjoy our movie recommendations, make sure you have the following dependencies installed:

- Python 3.6+
- Streamlit
- Pandas
- Scikit-learn
- NumPy

You can easily install these dependencies using `pip`:

```bash
pip install streamlit pandas scikit-learn numpy or requirement.txt
```

## How to Run

To experience the magic of movie recommendations, follow these simple steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/Abhishek676062/Movie-Recommended-System.git
```

2. Change into the project directory:

```bash
cd Movie-Recommended-System
```

3. Run the Streamlit app:

```bash
streamlit run app.py
```

4. The app will now be accessible through your web browser at `http://localhost:8501`.

## Usage

Our user-friendly interface makes it effortless to discover movies you'll love. Here's what you can do:

- **Search**: Type in the title of a movie you enjoyed, and our system will recommend similar movies that match your tastes.
- **Rate**: Rate movies you have previously watched, and the recommendation engine will tailor its suggestions based on your preferences.
- **Explore**: Explore a curated selection of popular and trending movies to find something new and exciting.

The system will generate a list of recommended movies, complete with insightful details and options to watch trailers or find more information.

## Acknowledgments

We would like to extend our gratitude to the following:

- **TMDB**: For providing the comprehensive movie dataset that makes this project possible.
- **Streamlit**: For empowering us to build an interactive and user-friendly web app with ease.

## About Us

This project is a result of the collaborative effort of passionate movie enthusiasts and data scientists. Our goal is to enhance your movie-watching experience and introduce you to films that match your unique preferences.

If you have any questions, suggestions, or feedback, feel free to reach out to us at [shabhishek055@gmail.com](mailto:shabhishek055@gmail.com). We'd love to hear from you!

Happy movie recommendation exploring! 🎬🍿
