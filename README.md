# MOVIE RECOMMENDATION SYSTEM
There are mainly three methods to build a recommendation system:
### 1. Popularity based recommendation system
It is based on comparing popularity of movies. 
### 2. Content based recommendation system
In this movies are ranked based on similarity scores (it can be calculated by dot product, cosine angle or euclidean distance).
## 3. Collaboration Filtering based recommendation system :-
There are two different types of approaches used in this type:
key difference between both methods is that in memory based , there is no parameter learning but in model based there is parameter learning. In memory based approach closest users or items are calculated bu using Cosine similarity or Pearson correlation coefficients.
### 3.1 Memory based:-
This is further divided into two parts:-
i) user-based collaborative filtering
example - Users who are similar to you also liked
ii) item-based collaborative filtering
example - Users who liked this item also liked
### 3.2 Model based:-
These are generally machine learning models trained using different optimization algorithms like gredient descent , RMS prop, Momentum, Adam etc.
Types of modeling approaches are :-
i) Clustering based algorithm like KNN.
ii) Matrix factorization algorithm like SVD, probabilistic Matrix.
iii) Deep Learning where multi layered neural nets are trained.


## About Our Implementation
We have implemented two different methods
#### item-based collaborative filtering
we have used pearson correlation matrix for finding similarity between two matrices.
#### Matrix Factorization
We have used gredient descent algorithm train our model's parameters.


 Our dataset consists of 100,000 ratings of movie which is subset of MovieLens dataset. we have included link for dataset and also dataset in this repository.
 Firstly there is data visualization with various methods and then we have implemented item based collaborative filtering and then matrix factorization.
 We have also one interactive graph based on user data which can be seen by running the python notebook.You can see the screenshot for the same in this repository.
 Lastly we have one video of running the notebook and training the model.