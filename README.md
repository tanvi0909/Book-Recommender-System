# Book Recommender System

A Book Recommender System that suggests books to users based on both popularity and user-based collaborative filtering. This project includes data analysis, recommendation model training, and deployment of a web app using Flask, with hosting on Render.

Check it out here 
https://book-recommender-system-4dcq.onrender.com

<img align="center" alt="ai" src="https://github.com/tanvi0909/assets/blob/main/book-recommend.jpg" height="500" width="900"/>


## Project Overview

The Book Recommender System utilizes two main recommendation techniques:
- **Popularity-Based Recommendation**: Recommends books with the highest average ratings.
- **Collaborative Filtering**: Uses cosine similarity for personalized recommendations based on user preferences.

## Datasets

The project includes the following datasets:
- **Books**: Contains details about each book, including title, author, and genre.
- **Users**: Information about the users.
- **Ratings**: User ratings for different books.

## Files

- `book-recommender-system.ipynb`: Jupyter notebook with data analysis and model development.
- `app.py`: Flask app file to load the recommendation models and serve recommendations.
- `popular_books.pkl` and `collaborative_books.pkl`: Pickle files storing recommendation models for popularity-based and collaborative filtering recommendations.

## Project Workflow

1. **Data Analysis**:
   - Performed exploratory data analysis (EDA) on the datasets, focusing on numerical, categorical, and bivariate analysis.

2. **Model Development**:
   - **Popularity-Based Recommender**: Based on average ratings, recommends books with high popularity.
   - **Collaborative Filtering**: Utilized cosine similarity to find similar books based on user ratings.

3. **Model Serialization**:
   - Saved models in `pkl` format for easy loading in the Flask app.

4. **Web Application**:
   - Built a Flask web application (`app.py`) to serve recommendations.
   - Created a front-end to display recommended books.

5. **Deployment**:
   - Deployed the application on [Render](https://render.com/) for accessibility.

## How to Run the Project

1. **Install Required Packages**:
   - Install dependencies from `requirements.txt` (Flask, pandas, scikit-learn, etc.).

2. **Run the Flask Application**:
   - Start the Flask app by running:
     ```bash
     python app.py
     ```

3. **Access the Web App**:
   - Open your web browser and navigate to `https://book-recommender-system-4dcq.onrender.com` to access the recommender system.


