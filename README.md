# How to Run

Download the following datasets from Julian's website:
1. `australian_user_reviews.json.gz`
2. `australian_users_items.json.gz`
3. `steam_games.json.gz`

Place themn in a directory called `dataset`



# Baselines
1. **Random Prediction**: 0.4994 Accuracy, 0.4996 AUC
2. **Popularity Baseline**: 0.8749 Accuracy, 0.9454 AUC

# Methods
1. **Matrix Factorization**: 
    - Training: 0.8775 Accuracy, 0.9526 AUC
    - Test: 0.8767 Accuracy, 0.9516 AUC