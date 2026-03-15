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

Distribution of Spotify Track Popularity

What this chart shows

This histogram visualizes the overall distribution of popularity scores across all tracks in the dataset.

Interpretation

- Most songs fall between 20–60 popularity score.

- Very few songs reach extremely high popularity (>80).

- The distribution is right-skewed, meaning blockbuster hits are rare.

- This confirms that most tracks perform moderately rather than becoming major hits.

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
