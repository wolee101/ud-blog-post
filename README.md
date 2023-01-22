README.md - SF Airbnb Data Analyses


## **Project Title**

**SF Airbnb Data Analyses -  Udacity Blog Post Project**


## **Description**

According to statistics available on Google, there are 150 million Airbnb users that can choose from 1.9 million listings in 65,000 cities around the world at any given time. I myself have tried to use Airbnb once but the host ended up cancelling the day I was checking in because the place had not yet been cleaned. It was an extremely unpleasant experience but I decided not to post a negative review. However, this made me become curious about the characteristics of properties and their hosts, as well as the validity of reviews. I also became interested in finding out how many negative reviews were actually posted.

Because I live in the Bay area I chose to look at San Francisco to find the answers to my questions. The city does not represent all Airbnb listings nor reviews. This is just a project meant to satisfy my curiosity and to conduct some analysis on one of the most visited cities in the United States.



Below are my research questions I tried to answer using data from Airbnb listings and reviews in San Francisco.

**Research Questions:**



1. What are the characteristics of Airbnb listings in San Francisco?
2. What are the differences between listings owned by superhosts and non-superhosts?
3. What is the average review score?
4. What percentage of reviews are positive or negative? Are there any gender differences in review writing behavior?
6. What are the most common words people say in their reviews?


**Dataset Used:**

San Francisco Airbnb listings and reviews data compiled on 8/6/2019 (available at http://insideairbnb.com/get-the-data.html).

**Analyses Used:**

Descriptive, regression, classification, and text analyses


## **Dependencies and Installation**

You need to install the following python, nlp, and visualization packages and libraries:


*   pandas: pip install pandas
*   numpy: pip install numpy
*   nltk: pip install nltk
  -   nltk stopwords: nltk.download (‘stopwords’) in jupyter notebook
  -   nltk sentiment lexicon: nltk.download (‘vader_lexicon’) in jupyter notebook
*   gender guesser: pip install gender_guesser.detector
*   scikit-learn: pip install scikit-learn
*   gensim: pip install gensim
*   spacy: pip install spacy
  -   language detector: pip install spacy-langdetect
*   matplot: pip install matplotlib
*   seaborn: pip install seaborn
*   mapply: pip install mapply

To start a live Jupyter session without installing dependencies, click the Binder link button below.


[![Binder](http://34.94.204.67/badge_logo.svg)](https://binder.gsbdarc.com/v2/gh/wolee101/ud-blog_post/master?labpath=Airbnb_data_analysis.ipynb)


## **Acknowledgments**



*   Udacity course materials
*   Countervectorizer tutorial on Kaggle: [https://www.kaggle.com/adamschroeder/countvectorizer-tfidfvectorizer-predict-comments](https://www.kaggle.com/adamschroeder/countvectorizer-tfidfvectorizer-predict-comments)
*   Christhian Boujon’s github code on the top n number: [https://gist.github.com/CristhianBoujon/c719ba2287a630a6d3821d37a9608ac8](https://gist.github.com/CristhianBoujon/c719ba2287a630a6d3821d37a9608ac8)



<!-- Docs to Markdown version 1.0β17 -->
