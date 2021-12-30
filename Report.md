# Abstract
The main focus of this project is predict a tags topic modeling to predict the correct tag of quote can correctly classify the topic.

# Design:
Using supervised and semi-supervised learning with Natural Learning Processing (NLP), throughout the project we will categorize the tag category based on the quote.So that when someone writes this quote it will give a quote similar to the quote's category.


# Data:
We have 2 dataset  the first one from Kaggel consist of 499,709 with 3 features and the second one web scraping from goodreads contain 83,618 with 3 features.
After pre-processing we decide to used data from kaggel because it is more useful, specifically the length of the quotes and topic modelling. The features consist of quotes, authers and category

# Algorithms
1. Exploratory Data Analysis was done to the dataset.
  - **Cleaning**
      - Checked for nulls values.
      -  Checked for duplicates and remove.
      -  SubSet of data: Quotes Where The length of word more than 150.
      -  Romoved unneeded columns.
  - **Natrual Langauge Processing**
       - Contraction
       - Tokenization
       - Remove Punctuations & Number
       - Remove Non english world
       - Remove rare and frequent words 
       - Remove stop world
       - Lowercase
       - Remove Repeating Char
       - Spell Corrections
       - Stemming
       - Lemmatization
       - Remove Word Less Than 3
       - Remove Verbs

2. Topic Modeling
- Non-Negative Matrix Factorization (NMF).
- Latent Semantic Analysis (LSA).
- Latent Dirichlet Allocation (LDA).
- CorEx
- CorEx With Anchors


3. Classification
- 2 classification models were built:
    
    -  Logistic Regression
    -  Random Forest


## Tools:
* Software Platform :Jupyter Notebook
* Programming Language: Python
* Python Libraries:
  * Statistics libraries:
  * Sklearn
  * nltk
  * SpaCy
* Data manipulation libraries:
  * Pandas
  * Numpy
* Visualization libraries
  * Matplotlib
  * Seaborn
  * wordcloud
* Storage libraries
  * Pickle

# Conclusion

CoreEx with Anchors the best in displaying topics.
