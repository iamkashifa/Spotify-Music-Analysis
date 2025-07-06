# Spotify Popularity Analysis 🎵

An in-depth analysis of Spotify track data to uncover the key drivers of music popularity. This project explores audio features, genre trends, and playlist characteristics to understand what makes a song a hit.

## Project Overview

This project aims to dissect the anatomy of a popular song on Spotify. By analyzing a comprehensive dataset of tracks, we seek to answer several key questions:
- What are the most dominant genres on the platform?
- Which audio features, such as **danceability**, **energy**, and **valence**, are most common in top-charting songs?
- How significant is a song's inclusion in a major playlist to its overall popularity?
- Is there a correlation between a song's release date and its popularity?

The analysis was conducted using Python in a Jupyter Notebook, with the final insights and visualizations compiled into a summary presentation.

---

## The Dataset

The data for this project was sourced from **Kaggle** and is derived from the official Spotify API. It contains detailed information for over 30,000 tracks across various playlists.

Key attributes in the dataset include:
- **Track Metadata:** `track_name`, `track_artist`, `track_album_name`
- **Popularity Score:** `track_popularity` (a score from 0-100)
- **Playlist Information:** `playlist_name`, `playlist_genre`, `playlist_subgenre`
- **Audio Features:** `danceability`, `energy`, `loudness`, `speechiness`, `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`

---

## Key Findings & Visualizations

Our analysis uncovered several significant trends that contribute to a song's popularity on Spotify.

### 1. Genre Dominance
The most popular genres are consistently **Pop**, **Rap**, and **Rock**. These genres have the highest average popularity scores and feature most frequently in high-traffic playlists.

### 2. The Anatomy of a Hit Song
Popular tracks generally exhibit higher **energy** and **danceability** scores. This suggests that upbeat, dance-friendly music has a broader appeal among Spotify listeners.

### 3. The Power of Playlists
Inclusion in a major curated playlist is a massive driver of a track's popularity. Playlists like "Today's Top Hits" and "RapCaviar" act as powerful discovery engines, significantly boosting a song's streams and visibility.

### 4. Newer is Better
The analysis reveals a strong trend where newer music achieves higher popularity scores. This indicates that listeners are actively engaged with recent releases and that the platform prioritizes fresh content.

### 5. Audio Feature Correlations
- **Positive Correlation:** `energy` and `loudness` are strongly correlated, as are `energy` and `valence` (the musical "positiveness" of a track).
- **Negative Correlation:** `acousticness` and `energy` are negatively correlated, suggesting that more acoustic tracks are typically lower in energy.

---

## Tools & Libraries

This project leverages the power of Python and its data science ecosystem:

- **Python 3.x**
- **Jupyter Notebook** for interactive analysis and visualization
- **Pandas** for data manipulation and cleaning
- **Matplotlib** & **Seaborn** for creating insightful visualizations
- **openpyxl** for reading and handling `.xlsx` files

---

## Project Files

- `spotify.xlsx`: The raw dataset containing track and audio feature information.
- `spotify.ipynb`: The complete Jupyter Notebook with all Python code for data loading, cleaning, analysis, and visualization.
- `spotify presentation.pptx`: A presentation summarizing the project's methodology, key findings, and strategic implications.
- `README.md`: This file!

---

## How to Run This Project

To replicate this analysis on your own machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd your-repository-name
    ```

3.  **Install the necessary libraries:**
    ```bash
    pip install pandas matplotlib seaborn openpyxl jupyter
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

5.  Open and run the cells in `spotify.ipynb` to see the complete analysis from start to finish.

---

## Implications

The insights from this project have practical applications for various players in the music industry:
- **For Artists & Labels:** Understanding which audio features and genres are trending can inform the creative process and marketing strategies to maximize a song's potential for success.
- **For Spotify:** The findings can help refine recommendation algorithms and playlist curation to enhance user engagement and satisfaction.
- **For Marketers:** The data underscores the critical importance of playlist-focused promotional campaigns for driving track discovery and popularity.
