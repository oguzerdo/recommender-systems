# Hybrid Recommender System

This repo contains the following recommender systems.

- Association Rule Learning Recommender
- Content Based Recommender
- Item Based Recommender
- User Based Recommender
- Matrix Factorization Recommender

Contains a project that is a hybrid method of the above methods.

![Untitled](/images/project.png)

# Business Problem

For the user whose ID is given, it is desired to make 10 movie recommendations using `item-based` and `user-based` recommender methods

# Dataset Info

### movie.csv

| Feature | Definition |
| --- | --- |
| movieId | Unique movie ID |
| title | Movie title |
| genres | Movie genre |

### rating.csv

| userId | Unique User ID |
| --- | --- |
| movieId | Unique Movie ID |
| rating | Rating given to the movie by the user |
| timestamp | Review data |


# Requirements

```
mlxtend==0.21.0
pandas==1.4.4
scikit_learn==1.1.2
scikit_surprise==1.1.2
surprise==0.1
```

# **Files**

*[01_arl.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/01_arl.ipynb) -* Association Rule Learning Notebook

*[02_content_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/02_content_based_recommender.ipynb) -* Content Based Filtering Movie Recommender

*[03_item_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/03_item_based_recommender.ipynb) -* Item Based Filtering Movie Recommender

*[04_user_based_recommender.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/04_user_based_recommender.ipynb) -* User Based Filtering Movie Recommender

*[05_matrix_factorization.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/05_matrix_factorization.ipynb) -* Matrix Factorization Movie Recommender

*[06_Hybrid-Recommender-System-Project.ipynb](https://github.com/oguzerdo/recommender-systems/blob/main/06_Hybrid-Recommender-System-Project.ipynb) -* Hybrid Movie Recommender PROJECT

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)