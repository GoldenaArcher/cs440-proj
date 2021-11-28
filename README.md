# CS440 Recommender System

## Tool/Data Used

- [Amazon Product Data](https://jmcauley.ucsd.edu/data/amazon/)

- [Microsoft Recommenders](https://github.com/microsoft/recommenders)

  Since the goal is to evaluate how well the algorithm works, the used alogrithm used in comparison is:

  - Cornac/Bilateral Variational Autoencoder (BiVAE)

    Collaborative Filtering

  - Cornac/Bayesian Personalized Ranking (BPR)
    Collaborative Filtering
  - LightGCN

    Collaborative Filtering

  - Simple Algorithm for Recommendation (SAR)

    Collaborative Filtering

  - Surprise/Singular Value Decomposition (SVD)

    Collaborative Filtering

  - Neural Collaborative Filtering (NCF) -> pretty slow, may drop this one

    Collaborative Filtering

## Sample provided by Microsoft

Below a list of jupyters that I can successfully run on my machines:

- [Cornac/Bilateral Variational Autoencoder (BiVAE)](examples/cornac_bivae_deep_dive.ipynb)

- [Cornac/Bayesian Personalized Ranking (BPR)](examples/cornac_bpr_deep_dive.ipynb)
-
- [LightGCN](examples/lightgcn_deep_dive.ipynb)
- [Simple Algorithm for Recommendation (SAR)](examples/sar_movielens.ipynb)
- [Surprise/Singular Value Decomposition (SVD)](examples/surprise_svd_deep_dive.ipynb)
- [Neural Collaborative Filtering (NCF)](examples/ncf_deep_dive.ipynb)

## Lab with result

- [x] [Lab Bivae](./lab/Lab_Bivae.ipynb)
- [x] [Lab BPR](lab/Lab_BPR.ipynb)
- [x] [Lab NCF](lab/Lab_NCF.ipynb)
- [x] [Lab SAR](lab/Lab_SAR.ipynb)
- [x] [Lab SVD](lab/Lab_SVD.ipynb)
- [ ] [Lab Light GCN](lab/Lab_LIGHT_GCN.ipynb)
