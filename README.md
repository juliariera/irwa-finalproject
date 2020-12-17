# Search engine for US 2020 Elections 
The main goal of the project is to build a search engine that, given a query, returns the relevant tweets related to it in a ranking.

Usage
------
This repository contains 3 folders. The search-engine one contains the code and data to run the search engine. The first part of the notebook contains the code used to collect the data, then, there is an analysis of that data and finally, all the code to run the search-engine. To only run the search engine using the previously collected data, run the imports cell and go directly to the "2. Search engine", part of the code. Then, all the code that follows is used to pre-process the data and build all the necessary things to create a search engine. The code to create the wordcloud and barplot is also there, although it does not have to be run when running the search engine. There are two types of ranking: the tf-idf classical one and an own ranking based also on the popularity of the tweets.

In the notebook folder, we have the three notebooks, one for each research question. Only the first one is implemented. In this first RQ, it is asked to run the previously created search engine ranking by tf-idf and afterwards to create a word2vec (or, in fact, tweet2vec) representation of the tweets and use it along with cosine similarity also to rank the tweets. Then a two dimensional scatter plot through the t-sne algorithm is generated to visualize the tweets. 

Prerequisites
------
To be able to use the notebooks tweepy, gensim and wordcloud must be downloaded.

Author
------
[Júlia Riera Perramón](https://www.linkedin.com/in/julia-riera-perramon/) (julia.riera02@estudiant.upf.edu)
