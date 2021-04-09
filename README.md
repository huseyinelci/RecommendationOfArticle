# Recommendation of Article with IBM Watson Studio datasets

In this project, I Developed a recommendation engine based on user behavior and social network. Used Rank Based, User-User Based Collaborative Filtering and SVD Matrix Factorization to accomplish system

## Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Project Tasks](#task)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

<a name="installation"></a>
## Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.7.6

<a name="motivation"></a>
## Project Motivation
This project is focusing on the interactions of articles and user who reads the article to provide a list of recommendations to the users by performing a data analysis on real data from the IBM Watson Studio platform. The main purpose of this project is finding the most suitable recommendations method as well as using svd method for predicting the user preference.

<a name="tasks"></a>
## Project Tasks 
This project will be divided into the following tasks

0. Loading Libraries - Loading and Inspection of Datasets

1. Exploratory Data Analysis - Before making recommendations of any kind, we will need to explore the data we are working with for the project. Dive in to see what we can find. There are some basic, required questions to be answered about the data we are working with throughout the rest of the notebook. Use this space to explore, before we dive into the details of our recommendation system in the later sections.

2. Rank Based Recommendations - To get started in building recommendations, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering - In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. We will implement this next.

4. Content Based Recommendations - Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using our NLP skills, we might come up with some extremely creative ways to develop a content based recommendation system. We are encouraged to complete a content based recommendation system.

5. Matrix Factorization(user-item collaborative filtering with SVD without regularization) - Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with (spoiler alert - it isn't great). We will finally discuss which methods we might use moving forward, and how we might test how well our recommendations are working for engaging users.

6. Extras

<a name="files"></a>
## File Descriptions 
There is a notebooks available here to showcase work related to the above questions.\
<br>
The notebooks contains my steps for making the recommendation for users/article readers based on the data analysis of the database provide within.\
<br>
Detail explanations are included to help  you walking throught process. 

```text
Recommendation-of-Article/
├──── README.md
├──── Recommendations_with_IBM.ipynb # Jupyter Notebook with python codes
├──── Recommendations_with_IBM.html  # Html page of this project
├──── user_item_matrix.p             # If need User-Item matrix
├──── project_tests.py               # Test of this project
├──── top_10.p                       # Top 10 list for recommendation
├──── top_20.p                       # Top 20 list for recommendation
├──── top_5.p                        # Top 5 list for recommendation
├──── data/
     ├──── articles_community.csv        # Articles data for process
     └──── user-item-interactions.csv    # Interactions of User-Item data for process
└──── image/
     └──── IBM.jpeg
```



<a name="results"></a>
## Results
The main findings of the code can be found with python code inside the jupyter notebooks.


<a id="licensing"></a>
## Source, Licensing, Authors, and Acknowledgements

#### Source and  Licensing
The **dataset** owner is [IBM Watson Studio](https://www.ibm.com/watson/) Also, if _you plan to use this database in your article research or else_ you must taken and read main Source in the **IBM Watson**.

#### Authors
Huseyin ELCI <br>
[Github](https://github.com/huseyinelci)  |  [Kaggle](https://www.kaggle.com/huseyinelci)  |  [Linkedin](https://www.linkedin.com/in/huseyinelci/)
#### Acknowledgements
Thanks to **[IBM Watson Studio](https://www.ibm.com/watson/)** for providing cool data with which we can create a cutting edge project.

---
<a id="Conclusion"></a>
## Conclusion
**It was instructive, it was worth it.** You could touch the code. Have a enjoy. **:)**
