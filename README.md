# spotify-popularity-analysis

Exploratory data analysis of Spotify tracks to understand how audio features relate to song popularity.

This project explores how Spotify audio features relate to track popularity.

## Objectives
- Analyze relationships between audio features and popularity
- Identify nonlinear patterns in feature behavior
- Compare top performing tracks vs low performing tracks

## Dataset
Spotify track dataset (~80k tracks after cleaning)

## Visualization and Interpretation
# Average Popularity Across Audio Feature Levels

![Average Popularity Across Audio Feature Levels](images/{3B01A2D7-C3BA-4CD4-A02E-897212C08850}.png)


This visualization explores how track popularity changes as the intensity of different audio features increases.

Features analyzed:

- Energy

- Danceability

- Valence (positiveness)

- Acousticness

Interpretation

- Energy: Popularity increases with moderate energy but drops at extremely high energy levels.

- Danceability: Songs with higher danceability tend to achieve higher popularity.

- Valence: Moderately positive songs perform better than extremely sad or extremely happy songs.

- Acousticness: Highly acoustic songs tend to have lower popularity, suggesting mainstream tracks favor produced sounds.

Key insight:
Moderate levels of energy and emotional balance tend to correlate with higher popularity.
-
# Distribution of Spotify Track Popularity

![Distribution of Spotify Track Popularity](images/{7900E9A0-F1D7-4A3D-B9C1-751FC5A4A09B}.png)

This histogram visualizes the overall distribution of popularity scores across all tracks in the dataset.

Interpretation

- Most songs fall between 20–60 popularity score.

- Very few songs reach extremely high popularity (>80).

- The distribution is right-skewed, meaning blockbuster hits are rare.

- This confirms that most tracks perform moderately rather than becoming major hits.

Key insight:
Most songs on Spotify achieve moderate popularity scores (roughly between 20–60), while extremely high-popularity tracks are relatively rare. This indicates that viral or blockbuster hits represent only a small fraction of all released music, suggesting that success on streaming platforms is concentrated among a limited number of tracks while the majority perform at average levels.
-
# Audio Feature Profile: Top 10% vs Bottom 10% Tracks

![Audio Feature Profile: Top 10% vs Bottom 10% Tracks](images/{8C02D6B1-DF46-4D53-BF87-49B95CD04F31}.png)

This comparison highlights the average audio feature values for:

* Top 10% most popular tracks

* Bottom 10% least popular tracks

Features compared:

- Danceability

- Energy

- Valence

- Acousticness

- Loudness

- Speechiness

- Instrumentalness

Interpretation

Key differences observed:

- Top tracks are generally louder

- Higher danceability is associated with popularity

- Less acoustic and less instrumental songs perform better

- Speechiness shows minimal impact

Key insight:
Hit songs tend to be loud, energetic, and danceable, aligning with mainstream listening preferences.
-
## Analysis Performed
- Data cleaning
- Feature distribution analysis
- Correlation heatmaps
- Nonlinear feature bin analysis
- Feature interaction heatmap
- Top vs Bottom 10% comparison

## Key Insights
- Audio features show weak linear correlation with popularity.
- Popular tracks tend to lie in moderate ranges of energy and danceability.
- Extremely high or low feature intensities underperform.
- External factors (marketing, playlist placement, timing) likely play a major role in popularity.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- SciKitLearn
