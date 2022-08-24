<h1 align="center"> Unsupervised Learning Capstone Project </h1>

<h2 align="center"> Book Recommendation Engine </h2>

<p align="center"> 
  <img src="Image/book.jpg" alt="book.jpg">
</p>

![------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

In e-commerce companies (Amazon, Flipkart, Myntra etc.) and consumer internet companies (Spotify, YouTube, Uber etc.) today, contents available for users to explore are overwhelming because an average online website is about 70% more than a physical store in total number of users and items. Hence, the need to filter, prioritize and efficiently deliver relevant information using recommender systems becomes the need of the time.

The Recommendation System belongs to the class of Information Retrieval, Data Mining and Machine Learning. Recommender systems recommend items to users such as books, movies, videos, electronic products and many other products in general. Recommender systems help the users to get personalized recommendations, helps users to make correct decisions in their online transactions, increase sales and redefine the users web browsing experience, retain the customers, enhance their shopping experience etc. Recommender system has the ability to predict whether a particular user would prefer an item or not based on the user's profile. Recommender systems are beneficial to both service providers and users. They reduce transaction costs of finding and selecting items in an online shopping environment.

![------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 align="center"> Introduction </h2>

1. Collaborative Recommender System
Collaborative recommender systems aggregate ratings or recommendations of objects, recognize commonalities between the users on the basis of their ratings and generate new recommendations based on inter-user comparisons. The greatest strength of collaborative techniques is that they are completely independent of any machine-readable representation of the objects being recommended and work well for complex objects where variations in taste are responsible for much of the variation in preferences. Collaborative filtering is based on the assumption that people who agreed in the past will agree in the future and that they will like similar kinds of objects as they liked in the past.

2. Content-Based Recommender System
A content-based recommender learns a profile of the new user’s interests based on the features present, in objects the user has rated. It’s basically a keyword specific recommender system where keywords are used to describe the items. Thus, in a content-based recommender system the algorithms used are such that it recommends users similar items that the user has liked in the past or is examining currently.

![------------------------------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 align="center"> Datasets Used </h2>

1. Books Dataset
The features of the dataset were as follows:
* ISBN: Unique ID to identify a book
* Book-Title: Title of the book
* Book-Author: Author of the book
* Year-Of-Publication: The year in which the book was published
* Publisher: Publisher of the book
* Image-URL-S: Image URL of the book (Small Size)
* Image-URL-M: Image URL of the book (Medium Size)
* Image-URL-L: Image URL of the book (Large Size)

2. Users Dataset
The features of the dataset were as follows:
* User-ID: Unique ID of the user
* Location: Location of the user
* Age: Age of the user

3. Ratings Dataset
The features of the dataset were as follows:
* User-ID: Unique ID of the user
* ISBN: Unique ID to identify a book
* Book-Rating: Ratings of the book (In the range of 0-10)
