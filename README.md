# CS440 Recommender System

## Tool/Data Used

- [Amazon Product Data](https://jmcauley.ucsd.edu/data/amazon/)

- [Microsoft Recommenders](https://github.com/microsoft/recommenders)

    Since the goal is to evaluate how well the algorithm works, the used alogrithm used in comparison is:

    - Cornac/Bilateral Variational Autoencoder (BiVAE)
    - Cornac/Bayesian Personalized Ranking (BPR)
    - LightGCN
    - Simple Algorithm for Recommendation (SAR)
    - Surprise/Singular Value Decomposition (SVD)

    - Neural Collaborative Filtering (NCF) -> pretty slow, may drop this one

## Sample provided by Microsoft

Below a list of jupyters that I can successfully run on my machines:

- [Cornac/Bilateral Variational Autoencoder (BiVAE)](examples/cornac_bivae_deep_dive.ipynb)