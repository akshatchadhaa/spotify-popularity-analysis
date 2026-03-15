# spotify-popularity-analysis

Exploratory data analysis of Spotify tracks to understand how audio features relate to song popularity.

This project explores how Spotify audio features relate to track popularity.

## Objectives
- Analyze relationships between audio features and popularity
- Identify nonlinear patterns in feature behavior
- Compare top performing tracks vs low performing tracks

## Dataset
Spotify track dataset (~80k tracks after cleaning)

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
