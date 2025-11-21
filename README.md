# How to Run

Download the following datasets from Julian's website:
1. `australian_user_reviews.json.gz`
2. `australian_users_items.json.gz`
3. `steam_games.json.gz`

Place themn in a directory called `dataset`



# Baselines
1. **Random Prediction**: 0.4994 Accuracy
2. **Popularity Baseline**: 0.7660 Accuracy - with negative ratio 2:1

# Methods
1. **Matrix Factorization**: 
    - Training: 0.8775 Accuracy, 0.9526 AUC
    - Test: 0.8767 Accuracy, 0.9516 AUC

1. **Feature Engineering**:
With negative ratio 2:1:
    - Training: 0.8459 Accuracy
    - Test: 0.8470 Accuracy 
