# Restaurant-Recommendation-System_Using-PySpark-and-R
This repository contains the code for a Restaurant Recommendation System implemented using PySpark and R. The system leverages collaborative filtering techniques to provide personalized restaurant suggestions based on user preferences, ratings, and reviews.

## Dataset Description
The dataset used for building the recommendation system is stored in the Zomato.csv file. It consists of 17 columns and 56251 rows, containing information such as restaurant URL, address, name, online order availability, table booking option, rating, number of votes, phone number, location, and restaurant type. The dataset size is approximately 0.5 GB.
Dataset link : - https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants/data

## Methodology
The implementation of the recommendation system follows a two-phase approach:

## Phase I: Data Scraping
Data for each restaurant and each category was scraped individually, extracting 15 variables.
Variables include online order availability, table booking option, rating, votes, phone number, location, restaurant type, dish liked, cuisines, approx. cost, reviews list, and menu item data.
## Phase II: Recommendation System Development
Implemented a content-based recommendation system using collaborative filtering techniques.
Preprocessed the dataset, performed exploratory data analysis (EDA), and setup PySpark environment in Colab.
Created a recommendation function to suggest similar restaurants based on ratings and cuisine types.

## Results and Discussion
The recommendation system successfully provides personalized restaurant suggestions to users based on their preferences and past interactions. It enhances user experience on platforms like Zomato by offering tailored recommendations, improving engagement, and fostering repeat business.

Overall, this project demonstrates the capabilities of PySpark and R in analyzing large datasets and building powerful recommendation engines for the restaurant industry.

## How to Use
To use the recommendation system:
Clone the repository to your local machine.
Install the required dependencies.
Run the provided scripts and notebooks to explore the dataset and utilize the recommendation system.

## Contributors
## TANMAY TIWARI
## ABHINEET RAJ
## AYUSH MADURWAR
