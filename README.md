# Twitter-Scraping (7-21 December 2015)

Retrieve information from Twitter, build and analyze a network related to a keyword. All the data are stored in MongoDB.

In this project I practice my skills for downloading data from Twitter, storing them into MongoDB, and performing some graph operations.


#### Description of Twitter_download _1527821.ipyn

* First download at least 10,000 tweets, related to some popular keyword (e.g., immigra- tion), using the search API.
* Obtain the followers of the users who tweeted. Note that you need to wait quite some time for this part. I use multiple APIs, and the last part of the code is developed counting on these APIs.
* Store the information of the tweets and of the graph into MongoDB.
* Create the graph of the users and perform the operations you did in the first part.

#### Description of Twitter_graph _1527821.ipynb

Use the NetworkX package(Python) to perform the following simple operations:

* Compute and plot the degree distribution.
* Compute and the degree, closeness, betweeness, and PageRank centralities
* Compute the clustering coefficient of some of the nodes, and the clustering coefficient of the graph.
* Compute the connected components of the graph.
* Perform the k-core decomposition of the largest component.

