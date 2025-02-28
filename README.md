# Predicting Video Game Sales Trends Using Machine Learning

##  Members 
Taylor Beimel, Tyler Fregoso, Jose Garcia, Prince Sanchez

## Overview
We aim to predict future video game sales while identifying the key factors driving success in the gaming industry. Our hypothesis is that both game genre and release year are the primary predictors of sales success. By applying machine learning techniques, this project examines sales trends across various genres and years, providing valuable insights into market dynamics.

## Dataset
- **Source:** [Kaggle - Video Games Dataset](https://www.kaggle.com/datasets/atharvaingle/video-games-dataset)
- **Description:** Contains data on video game sales across multiple regions, including North America, Europe, Japan, and other global markets. 
- **Features Used:**
  - Year of release
  - Genre
  - Global Sales (in millions)
- **Munging:** We began our project by cleaning up the dataset - first dropping the features we didn't need, and then removing missing values from our key predictors and filling them in. Next, we converted the Year feature to int datatype. We also aggregated the sales data by both Year and Genre to identify any general trends. 

## Methods
- **Exploratory Data Analysis (EDA):** Plotted sales trends over time for different genres using matplotlib.
- **Machine Learning Model:** Trained a Linear Regression model for sales prediction from sklearn. 
- **Evaluation:** Used Mean Absolute Error (MAE) to assess model performance from sklearn.

## Results
We successfully processed and visualized the video game sales data, which helped us to idenfity trends across different genres over time. We found that the top 4 genres predicted to have the best sales were Shooting, Action, Role-Playing, and Sports. 
- Certain genres (e.g., Action, Shooter) showed a strong increase in sales over time.
- Sales peaked around the late 2000s, with a decline in recent years.
- Predictions suggest steady sales trends for dominant genres in the coming years.

## Discussion
Our research helped us to identify the top-selling genres, however more research could be done to further identify what genres do the best overall considering factors like popularity, replayability, user ratings, player community and support, and others. The tools we used to complete our research are widely known and free to use, so our research is very reproducible. 

## Summary
In this project, we explored video game sales trends and built a predictive model using Linear Regression. While our model captured broad trends, future improvements could enhance accuracy. 

## Sources
Random Forests - https://scikit-learn.org/stable/modules/ensemble.html#forest
