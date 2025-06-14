# Recommendation_system

*COMPANY* : CODTECH IT SOLUTION

*NAME* : Paramisha Malviya

*INTERN ID* : CT08DM1132

*DOMAIN* : Machine Learning

*MENTOR* : Neela Santosh

*DURATION* : 8 weeks

##To complete Task 4 of my internship, I focused on understanding how recommendation systems work . My aim was to build a basic movie recommendation system that could predict a user's rating for a movie based on the preferences of other users with similar tastes.i began the task by studying the base concepts of recommendation systems, such as user-item matrices and matrix factorization techniques like Singular Value Decomposition (SVD). I explored these topics through online learning platforms like YouTube and articles on machine learning blogs. Additionally, I explored the Surprise library in Python, which is used for building and evaluating recommendation systems.For my dataset, I then created prepaired an (1000 rows) Excel file that contains ratings provided by 100 users (user_1 to user_100) for various Marvel movies such as Avengers, Iron Man, Thor, Hulk, Black Panther, Captain Marvel, etc. The dataset includes user names, movie titles, and their numeric equivalents ranging from 1 to 5.to implement the system, I first loaded the Excel dataset into a pandas DataFrame. Then, I used the Reader and Dataset classes from the Surprise library to convert the data into a format suitable for collaborative filtering. I used SVD as my algorithm of choice to factorize the user-movie interaction matrix.After training the model on 80% of the data and testing it on the remaining , I evaluated its performance using RMSE (Root Mean Square Error) it is the metric that measures how accurate the predicted ratings are. As an example , I had the system predict whether user 'A' would like the movie Black Panther, which they hadn’t rated before. The system returned a predicted rating, and based on whether the value was 4 or above, the movie was recommended to the user.This project gave me practical exposure to how recommendation engines analyze behavior patterns to suggest relevant content. Through this, I learned not just how to build a simple movie recommendation system, but also understood its real-world applications like:
Entertainment Platforms, E-commerce – recommending products to shoppers,Education Tech – suggesting relevant courses or materials,News Portals – personalizing article recommendations,
Music Streaming – curating playlists based on listening patterns.Overall, this task helped me understand how collabrative filtering maked digital experiences by learning from
collective user behavior, and how matrix factorization improves the quality of recommendations even with limited data ##

#output

![Image](https://github.com/user-attachments/assets/ead5690c-4bb7-42b0-977c-c8d506f4f8f9)
