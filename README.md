# Recommendation Engines

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)

## Installation <a name="installation"></a>

To run the notebook install the packages listed in `requirements.txt`


## Project Motivation<a name="motivation"></a>

The objective of this project is analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles, using four approaches:

I. Rank Based Recommendations

Find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

II. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 

III. Content Based Recommendations 

We could also look at articles that are similar in terms of the words they share in their description. These similar articles could then be recommended to the users. 

VI. Matrix Factorization

Using the user-item interactions, we will build out a matrix decomposition. Using the decomposition, we will get an idea of how well we can predict new articles an individual might interact with. 


## File Descriptions <a name="files"></a>

* `Recommendations_with_IBM.ipynb`: Notebook with the code for the analysis.
* `Recommendations_with_IBM.html`: an html version of the notebook.
* `project_tests.py`: helper functions for tests.
* `top_5.p, top_10.p, top_20.p, user_item_matrix.p`: files used in helper functions.
* `requirements.txt`: packages required to run the notebook
