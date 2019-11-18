# IBM-Watson-Recommender-System

An exploration into various recommendation techniques using publicly available IBM Watson Studio's user and article data.

## Libraries Used

numpy<br/>
pandas<br/>
matplotlib<br/>
seaborn<br/>
pickle<br/>

```bash
pip install requirements.txt
```

## Motivation 

One aspect of keeping users happy and engaged is recommending great and relevant content for them. This project explores various ways to provide users with article recommendations that meet that criteria.

## Summary 

**Exploratory data analysis:** Basic visualizations and descriptive statistics on user-article interactions.

**Rank-based recommendations:** One way to address the cold start problem is with rank-based recommendations. Essentially, if we do not know anything about the user, we provide top ranked articles (by interaction count).

**User-user based collaborative filtering:** One of the most common ways to provide content recommendations is by finding users similar to the user in question, then suggesting content the similar user liked (or interacted with). This section explores multiple types of user-user collaborative filtering.

**Matrix Factorization:** Another type of collaborative filtering that works on user-item interaction matrixes. Particularly, Singular Value Decomposition (SVD) was employed since the user-item matrix contained no NaNs.
