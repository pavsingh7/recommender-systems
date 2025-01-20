# Introduction

This repository contains a collection of resources all pertaining to the topic of recommendation systems. The contents range from discussing the different types of recommendation systems to implementing them in code. Additionally, there are resources and articles covering the theory behind recommendation systems and how they work, as well as the state-of-the-art models and algorithms used in the field. For interest, articles on the ethical implications of recommendation systems and their use in the real world are also included.

# Recommenders

All can be found [here](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/).

- User-Based Collaborative Filtering ([ubcf_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/ubcf_recsys.ipynb))
- Item-Based Collaborative Filtering ([ibcf_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/ibcf_recsys.ipynb))
- SVD Matrix Factorization ([svd_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/svd_recsys.ipynb))
- Keyword Content-Based Filtering ([content_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/content_recsys.ipynb))
- Neural Collaborative Filtering ([ncf_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/ncf_recsys.ipynb))
- Alternating Least Squares ([als_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/als_recsys.ipynb))
- Deep Matrix Factorization ([dmf_recsys.ipynb](https://github.com/pavsingh7/recommender-systems/blob/main/recommenders/dmf_recsys.ipynb))



# Datasets

All can be found [here](https://github.com/pavsingh7/recommender-systems/blob/main/datasets/).

A lot of the datasets are sourced from the following repositories:

- https://github.com/caserec/Datasets-for-Recommender-Systems/tree/master
- https://www.kaggle.com/datasets/
- https://github.com/RUCAIBox/RecSysDatasets
- https://paperswithcode.com/datasets?task=recommendation-systems

Some popular datasets that have been made available or used in this repository are:

- [MovieLens Dataset](https://grouplens.org/datasets/movielens/). The goal of this dataset is to recommend movies to users based on their preferences. It contains explicit feedback in the form of ratings given by users to movies. There are various types of movielens dataset such as Movielens 1M, 20M, and 25M which means millions interactions between users and movies.

- [Pinterest](https://sites.google.com/site/xueatalphabeta/academic-projects). This dataset contains user-item interactions from Pinterest. The goal is to recommend pins to users based on their preferences. This dataset is not from official Pinterest that release the dataset. This is an academic project from Xue Geng et al from School of Computing, National University of Singapore. They published a paper namely [Learning Image](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Geng_Learning_Image_and_ICCV_2015_paper.pdf) and Users Features for Recommendation in Social Networks. 

- [Netflix](https://www.kaggle.com/netflix-inc/netflix-prize-data). In 2009, Netflix held the $1M Netflix Prize - a competition to improve their recommendation system by 10%. The goal is to predict the rating a user would give to a movie they have not yet rated. This dataset is then hosted in the Kaggle platform for anyone who wants to explore and create a model from it.

- [Amazon](http://jmcauley.ucsd.edu/data/amazon/). This dataset contains product reviews and metadata from Amazon, including 142.8 million reviews spanning May 1996 — July 2014. This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs). The goal is to recommend products to users based on their preferences or predict the rating a user would give to a product they have not yet rated.

- [Steam](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data). The dataset contains reviews from the Steam video game platform, and information about which games were bundled together. The goal is to recommend video games to users based on their preferences.

- [MIND](https://msnews.github.io/). MIND is one of the public dataset that Microsoft release for machine learning community. The dataset contains news articles and user interactions from the Microsoft News platform. The goal is to recommend news articles to users based on their preferences.

- [Million Song Dataset](http://millionsongdataset.com/). The Million Song Dataset is a freely-available collection of audio features and metadata for a million contemporary popular music tracks. The goal is to recommend songs to users based on their preferences. Provided by the Echo Nest, this dataset is a collaboration between LabROSA (Columbia University) and The Echo Nest.

- [LastFM](https://grouplens.org/datasets/hetrec-2011/). The dataset contains social networking, tagging, and music artist listening information from a set of 2K users from Last.fm online music system. The goal is to recommend music artists to users based on their preferences.

# Research Papers & Articles

