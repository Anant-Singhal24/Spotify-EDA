
## Project Title:
*DAI Assignment 1 - Spotify Dataset Analysis*
🛠 Instructions
⚠️ If this Python notebook does not open in GitHub or shows a rendering issue:

- Clone this repository and open the .ipynb file in Jupyter Notebook on your personal laptop.
- OR use nbviewer.org to view the notebook online.
- Download the file

## Author:
*Anant - 23112015
Chemical Engineering(CH1)*

## Project Overview:
This project analyzes trends in the Spotify 2023 dataset, focusing on various audio features, song popularity, and factors influencing music trends. The objective is to derive meaningful insights regarding song characteristics, user preferences, and market trends.

## Dataset:
The dataset consists of various attributes of Spotify songs, including:

- *Numerical Features:* Danceability, Valence, Energy, Acousticness, Speechiness, Loudness, Tempo, and Popularity.
- *Categorical Features:* Genre, Key, Mode, Year.

## Workflow:

### Data Cleaning:
- Handled missing or inconsistent values in the dataset.
- Converted data types where necessary to ensure consistency.
- Removed irrelevant columns that do not contribute to the analysis.

### Univariate Analysis:
- Distribution plots for numerical columns such as energy, valence, and danceability.
- Count plots for categorical columns such as mode, key, and genre.

### Outlier Detection & Handling:
- Boxplots were generated for numerical columns to visualize outliers.
- Extreme outliers were removed using the Z-score method (Threshold = 3).

### Bivariate Analysis:
- *Correlation Heatmap:* Visualizing relationships between numerical variables.
- *Scatter Plots:* Exploring relationships between features such as valence vs. energy.
- *Boxplots:* Understanding distributions of danceability, energy, and popularity across genres and modes.

### Multivariate Analysis:
- *Pairplots:* Exploring interactions between multiple features such as valence, energy, and acousticness.
- *Violin Plots:* Showing danceability distribution across different modes.
- *Pie Chart:* Displaying the distribution of songs in major and minor modes.
- *Heatmap:* Highlighting correlations between all key features.

### Additional Insights:
- Trends in Song Popularity Over the Years.
- Top Genres Based on Energy and Danceability.
- Relationship Between Loudness and Popularity.
- Influence of Valence on Song Popularity.
- Impact of Acousticness on Danceability.

## Results:
The project provides comprehensive insights into the characteristics of popular Spotify songs, identifying key trends in music composition and listener preferences. The analysis of danceability, energy, and other audio features reveals important factors that influence song popularity.

## Dependencies:
- numpy
- pandas
- matplotlib
- scipy
- seaborn
