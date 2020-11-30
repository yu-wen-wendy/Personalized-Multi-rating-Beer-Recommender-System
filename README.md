# Personalized-Multi-Rating-Beer-Recommender-System
Developed a recommender system that can handle multiple ratings by using correlation factors and collaborative filtering algorithms for personalized beer recommendations.

## Goal
Create a personalized recommendation system that helps people enjoy the best beer for them using novel multi-rating recommendation techniques. 

We aimed at finding out reasonable way to deal with multiple ratings, having better performance and reflecting users’ preference.


## Solution

### Methods
* Two recommendation methods: latent factor and collaborative filtering
* Compare single-rating algorithm and our suggestion of multi-rating handlings: 
- Single-rating: Use overall rating
- Multi-rating: User-preference-based aggregation algorithm
* Three evaluation methods: Overall RMSE/MAE, Top-N reommendations RMSE/MAE, Hit rate

### Structure

![This is a alt text.](/images/structure.png "Method")
Create a recommender system that aggregates the result of 4 single-rating recommender system based on each of the beer attributes and their weighted average.

### Related Work
Recommendation system has been developed with modern data mining techniques including preprocessing, dimensionality reduction, and various distance metrics. (Mehrbakhsh, 2016)
Collaborative filtering is the most widely used algorithm for recommendation system.(Badrul Munir, et al., 2001) 
Latent factor algorithm is derived to overcome the weakness of native collaborative filtering algorithm in dealing with challenging issues such as scalability, noises in dataset, and data sparsity. (Koren, Yehuda, Robert Bell, and Chris Volinsky, 2009)
Clustering methods are also applicable for picking representative values for recommendation such as k-means and spectral clustering. Especially, there was a trial that used spectral clustering to improve vulnerability of collaborative filtering. (Zhang, Zhuo, and Sanjeev R. Kulkarni, 2014)
Graph representation also has contributed to recommendation system. Link analysis and prediction also has contributed to recommendation system, to solve data sparsity problem. (Chen, Hsinchun, Xin Li, and Zan Huan, 2005) 


## Tools

### Libraries
scikit-surprise, scikit-learn

### Web Application
ReactJS


## Result 
Received A from the course "Data Mining" at KTH Royal Institute of Technology.

This project was done together with Heeje Lee (https://github.com/zedshape), Rachhek Shrestha(http://rachhek.github.io/), and Balint Kovacs.
