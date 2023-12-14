# WBSFLIX Recommendation Systems

## Goal
The goal of this project is to **develop recommendation systems** for Ursula, the owner of a hypothetical company named WBSFLIX, aiming to go digital. The aim is to replicate the user experience of popular platforms like NETFLIX. **Four distinct recommendation systems were implemented**: Popularity Ranking, Memory-Based Collaborative Filtering (User-Based and Item-Based), and a Random Recommender.

## Overview
WBSFLIX Recommendation Systems provide users with personalized movie suggestions based on different algorithms. 
1. The Popularity Ranking system suggests trending movies,
2. User-Based Recommender recommends movies similar to a selected one based on user preferences using cosine similarity
3. Item-Based Recommender suggests movies based on the similarity between items, providing alternatives similar to the chosen movie
4. Random Recommender adds an element of surprise to the recommendations.


## Approach
1. **Popularity Ranking:** Identified trending movies based on a combined metric of average ratings and the number of ratings.
2. **Memory-Based Collaborative Filtering (User-Based):** Recommended movies similar to a selected one, considering user preferences and using cosine similarity.
3. **Memory-Based Collaborative Filtering (Item-Based):** Suggested movies based on the similarity between items, providing users with alternatives similar to their chosen movie.
4. **Random Recommender:** Introduced an adventurous element by randomly recommending movies, diversifying the user experience.

## Deliverables
The project includes a **Google Colab notebook** [here]() containing the code for all recommendation systems, a **Python notebook** [here]() including the Streamlit code and the [URL]() for the deployed website. 
Since Streamlit glitches quite often, I also included a video of the finished product. 

![Streamlit Recommendation Systems](https://github.com/Cintia0528/Project-9-Recommender-Systems/assets/141332036/cf0f8fcf-cbbe-4afe-82ba-5890d18f03e7)


## Skills and Tools
- Python
- Streamlit
- Pandas
- NumPy
- Surprise
- scikit-learn

## Further Analysis
To enhance recommendation accuracy, in the future I aim to consider the following:
- **Enhanced Collaborative Filtering:** Explore advanced collaborative filtering techniques such as matrix factorization methods.
- **Content-Based Filtering:** Integrate content-based filtering to incorporate movie characteristics into recommendations.
- **Hybrid Models:** Combine multiple recommendation algorithms to leverage their strengths and improve overall accuracy.

