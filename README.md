# Search engine for US 2020 Elections 
The main goal of the project is to build a search engine that, given a query, returns the relevant tweets related to it in a ranking.

Usage
------
This repository contains 3 folders. The search-engine one contains the code and data to run the search engine. The first part of the notebook contains the code used to collect the data, then, there is an analysis of that data and finally, all the code to run the search engine. To only run the search engine using the previously collected data, run the imports cell and go directly to the "2. Search engine" part of the code. Then, all the code that follows is used to pre-process the data and build all the necessary things to create a search engine. The code to create the wordcloud and barplot is also there, although it does not have to be run when running the search engine. There are two types of ranking: the tf-idf classical one and an own ranking based also on the popularity of the tweets.

In the notebook folder, we have the three notebooks, one for each research question. Only part of the first one and part of the third one are implemented. In this first RQ, it is asked to run the previously created search engine ranking by tf-idf and afterwards to create a word2vec (or, in fact, tweet2vec) representation of the tweets and use it along with cosine similarity also to rank the tweets. In the third research question, a retweeted graph is build, splitted then by test and train sets. 

Finally, the other-outputs folder contains two pdf documents with the output of each of the search engine strategies used in the first folder, that is, the classical one and the one with the own ranking taking into account the popularity. Both runned with the same query to compare them. 

Prerequisites
------
To be able to use the notebooks, tweepy, gensim and wordcloud must be downloaded. All the code is develop in Jupyter Notebook. 
The data is uploaded with [Git LFS (Large File Storage)](https://git-lfs.github.com/). You must have it installed in advance to be able to open the data files.

Author
------
Júlia Riera Perramon (julia.riera02@estudiant.upf.edu)
