# BIGDATA-PROJ
Now a days many of us use Netflix, Hotstar and Prime that means we
are much reliable on these Online services rather than the offline or
cable operators. And also the e-books are available in like kindle etc….
After the evolution of the e-book system we purchase book online and
we get a copy and we read it.so here we are proposing an algorithm to
identify the related books to your previous reads and to recommend
the best books out of them.
Here in our project we consider a huge dataset of the books names and
their ratings after that we cluster the dataset by the method of kmeans. Clustering is always getting the similar type of things into one
cluster. Here the clustering is done based on the books that are read by
the user.
Whenever the user searches a book by the clusters we can find the
similar books in the same cluster we can display them as the
recommendation. i.e.. here we go for classification after the clustering
also known as clustered classification.
INTRODUCTION
We currently live in an era of information. We are surrounded by a
plethora of data in the form of reviews, blogs, papers and comments on
various websites. The number of people around the world who use the
internet has witnessed an increase of approximately 40% since 1995
and reached a count of 3.2 billion. The increased information flow has
opened more avenues, but it has also led to added confusion for the
user. Amidst this huge amount of data, the task of making certain 
decisions becomes difficult. It is rightly said that one should make an
informed decision, but too much information can also hinder the
decision-making process. Thus, in order to save a user from this
confusion and make the experience of surfing the internet a
pleasurable one, recommender systems were introduced. Francesco
Ricci, LiorRokach and BrachaShapira define the recommender systems
as software tools that make relevant suggestions to a user. Depending
upon the user profile and the product profile, which are formed using
various techniques and algorithms, suggestions are made. More than
32% of consumers rate a product online, over 33% writes reviews and
nearly 88% trust online ratings and reviews. So here we are proposing a
recommender system that clusters the books based on the ratings and
then produce recommendations.
LITERATURE SURVEY
Over the years, recommender systems have been studied widely and
are divided into different categories according to the approach being
used. The categories are collaborative filtering (CF), content based and
context based.
Types of recommendation systems
Collaboration filtering
Collaborative filtering (CF) uses the numerical reviews given by the user
and is mainly based upon the historical data of the user available to the
system. The historical data available helps to build the user profile and
the data available about the item is used to make the item profile. Both
the user profile and the item profile are used to make a
recommendation system. The Netflix Competition has given much 
popularity to collaborative filtering. Collaborative filtering is considered
the most basic and the easiest method to find recommendations and
make predictions regarding the sales of a product. It does have some
disadvantages which has led to the development of new methods and
techniques.
Content Based Recommender System
Content based systems focus on the features of the products and aim
at creating a user profile depending on the previous reviews and also a
profile of the item in accordance with the features it provides and the
reviews it has received. It is observed that reviews usually contain
product feature and user opinion in pairs. It is observed that users
reviews contain a feature of the product followed by his/her opinion
about the product. Content based recommendation systems help
overcome sparsity problem that is faced in collaborative filtering based
recommendation system.
Context Based Recommender System
Extending the user/item convention to the circumstances of the user to
incorporate the contextual information is what is achieved in contextbased recommender systems. This helps to abandon the cumbersome
process of making the user fill a huge number of personal details.
Hybrid-Based Filtering:
For the sake of improving recommendation effect, i.e. more
personalizing and more accurate, different recommendation methods
are combined and employed, forming a hybrid model. HF combines the
advantages of both collaborative, content-based filtering and other 
methods, which can have an integrated outcome and avoid their
individual limitations at the same time.
