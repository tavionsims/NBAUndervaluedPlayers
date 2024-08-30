# NBAUndervaluedPlayers

# Project Overview
This data science capstone project focuses on predicting a key basketball metric—True Shooting Percentage (TS%)—for NBA players. TS% is an advanced metric that evaluates a player's scoring efficiency by taking into account field goals, free throws, and three-point shots. Accurately predicting TS% can help NBA teams make strategic decisions regarding player trades, roster rotations, and free agency to optimize their offensive strategies and increase their chances of success.

# Key Steps in the Project:
Data Ingestion and Exploration:

The dataset, containing various player statistics from the 2022-2023 NBA season, is loaded and cleaned.
Descriptive statistics and visualizations provide insights into the distribution of the data and relationships between variables.
Data Visualization:

Histograms, pie charts, word clouds, and bar plots visualize the distribution of numerical features, player positions, team counts, and player names.
Heatmaps and line plots explore correlations and relationships between TS% and other metrics like Offensive Rating (ORtg), Effective Field Goal Percentage (eFG%), Usage Percentage (USG%), and Minutes Per Game (MPG).
Data Preprocessing:

Handling missing values by replacing them with zeros, as some statistics (like ORtg and DRtg) are unavailable for players with limited game time.
The dataset is split into features (X) and the target variable (y), where TS% is the prediction target.
Modeling and Evaluation:

Linear Regression Model: A linear regression model is trained on a portion of the data and evaluated on a test set. The model's accuracy is assessed using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
Decision Tree Model: A decision tree regressor is also trained and evaluated, offering a different perspective on the predictions.
Post-Processing and Analysis:

Players with high predicted TS% but limited minutes per game are identified as potential undervalued assets.
Visualizations, including scatter plots with regression lines, help compare the actual vs. predicted TS% and explore the relationship between predicted TS% and MPG.
Conclusion:
The project successfully predicts TS% using both linear regression and decision tree models. The analysis identifies key players who may be undervalued based on their predicted TS%, providing actionable insights for NBA team strategists. The results suggest that with further refinement, these models could play a significant role in helping teams optimize their rosters for future seasons.

# Future Work:
Enhancing model accuracy by incorporating more features or using advanced machine learning techniques.
Exploring other advanced metrics in conjunction with TS% to provide a more comprehensive player evaluation.
This project demonstrates the potential of data science in sports analytics, specifically in improving decision-making processes for NBA teams.
