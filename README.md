# Exploratory Data Analysis (EDA) on Spotify Data: Popular Hip-hop Artists and Tracks

This repository contains code and analysis for performing Exploratory Data Analysis (EDA) on the *Spotify Data: Popular Hip-hop Artists and Tracks*. The dataset contains a curated collection of approximately 500 entries showcasing the vibrant realm of hip-hop music.

## Dataset

The dataset provides a curated collection of
approximately 500 entries showcasing the vibrant realm of hip-hop music. These entries meticulously compile
the most celebrated hip-hop tracks and artists, reflecting their significant influence on the genre's landscape.
Each entry not only highlights the popularity and musical composition of the tracks but also underscores the
creative prowess of the artists and their profound impact on global listeners.

This dataset serves as a valuable resource for various data science explorations. Analysts can delve into trend
analysis to discern the popularity dynamics of hit hip-hop tracks over recent years. Additionally, the dataset
enables network analysis to uncover collaborative patterns among top artists, shedding light on the genre's
evolving collaborative landscape. Furthermore, it facilitates the development of predictive models aimed at
forecasting track popularity based on diverse features, offering insights for artists, producers, and marketers.

### Features:
- Artist: The name of the artist, providing direct attribution to the creative mind behind the track.
- Track Name: The title of the track, encapsulating its identity and essence.
- Popularity: A numeric score reflecting the track's reception and appeal among Spotify listeners.
- Duration (ms): The track's length in milliseconds, detailing the temporal extent of the musical experience.
- Track ID: A unique identifier within Spotify's ecosystem, enabling direct access to the track for further
exploration.

## Contents

- `spotify.csv`: CSV file containing the dataset.
- `spotify_eda.ipynb`: Jupyter Notebook containing the code for EDA.
- `README.md`: This README file providing an overview of the repository.

## Analysis

The EDA focuses on understanding the distribution and relationships between various clinical parameters in the dataset. Key aspects of the analysis include:

- Data cleaning and preprocessing.
- Univariate analysis to understand the distribution of individual features.
- Bivariate analysis to explore relationships between pairs of features.
- Visualization of findings using plots such as histograms, box plots, and scatter plots.

## Findings
1. Identify the top 5 popular artists based on the mean popularity of their tracks.Show the mean popularity of tracks for the top 5 popular artists Using BarPlot.

2. Determine the top 5 popular songs based on their popularity ratings.Display the popularity ratings of the top 5 popular songs using BarPlot.

3. Find the top 5 trending genres based on the mean popularity of tracks within each genre.Visualize the mean popularity of tracks for the top 5 trending genres.

4. Identify the top 5 longest songs among the tracks of the top 5 popular artists.Represent the duration of the top 5 longest songs among the tracks of the top 5 popular artists using BarPlot.

5. Determine the top 5 most danceable songs based on their danceability scores.Illustrate the danceability scores of the top 5 most danceable songs using PieChart.

## Requirements

To run the analysis, you need Python 3.x along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

You can install the required libraries using pip:
```
pip install pandas numpy matplotlib seaborn jupyter
```

