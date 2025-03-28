
### Overview
This project is a data analysis of the Steam Games dataset. The goal is to perform Exploratory Data Analysis (EDA) to uncover insights about the most popular games, their genres, and whether they are single-player or multiplayer. The analysis is done using Python libraries like Pandas, Matplotlib, and Seaborn.

### Dataset
The dataset used in this project is steam_games.csv, which contains information about games on the Steam platform. The dataset includes the following columns:

name: Name of the game.

release_date: Release date of the game.

all_reviews: Overall reviews of the game.

genre: Genre of the game.

game_details: Details about the game (e.g., single-player, multiplayer).

original_price: Original price of the game.

discount_price: Discounted price of the game.

### Project Goals
Analyze the most popular games based on reviews.

Identify the most popular genres.

Determine the distribution of single-player vs. multiplayer games.

Visualize trends in game releases and reviews over time.

### Steps
Data Cleaning:

Handle missing values.

Remove duplicates.

Convert data types (e.g., release_date to datetime).

### Data Analysis:
![Screenshot](https://raw.githubusercontent.com/pratham009/steam_data_analysis/main/images/powerbi.png)


Extract review counts from the all_reviews column.

Group data by year, genre, and game type (single-player/multiplayer).

Identify the top games and genres.

### Data Visualization:

Create visualizations like bar charts, line charts, and heatmaps to showcase insights.

### Conclusion
The analysis provides valuable insights into the most popular games, genres, and game types on the Steam platform. The visualizations help in understanding trends and patterns in the data. The project demonstrates how EDA can be used to extract meaningful information from a dataset and draw actionable conclusions.

### Insights
Most Popular Games:

Games like "Dota 2" and "Counter-Strike: Global Offensive" have the highest number of reviews.

Most Popular Genres:

Action and RPG genres are the most popular based on review counts.


### Game Type Distribution:

Multiplayer games tend to have more reviews compared to single-player games.

### Future Work
Predictive Analysis:

Predict game popularity based on features like genre, price, and release date.

Sentiment Analysis:

Analyze the sentiment of reviews to understand player satisfaction.
