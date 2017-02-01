# IMDB Movie Rating Prediction Study

An analysis, feature extraction and modeling study for https://github.com/sundeepblue/movie_rating_prediction dataset.

- `01 - Exploration.ipynb` is the exploratory analysis of the dataset. The correlations between features and IMDB score is investigated.
- `02 - Processing.ipynb` is where cleaning, imputation of the dataset is done. Also aggregated features from given ones are calculated, such as average score of directors, genres etc.
- `03 - IMDB Movie Rating Prediction Evaluation.ipynb` is where the features that are developed in the previous file are used in training of some ML models. A custom pipeline is written.

# Conclusion
In score prediction an order of magnitude reduction is observed over the baseline error according to `mean square error` metric.
