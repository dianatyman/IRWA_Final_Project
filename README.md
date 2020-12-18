# IRWA_Final_Project
Final Project of the subject of Information Retrieval and Web Analysis.

** SE_206747_205906.ipynb ** -Download to the same folder the tweets.json and import it.
 Run all cells, as they are necessary for the terminal to work correctly, the main menu to choose the ranking is titled with a markdown with “TERMINAL TO RUN THE SEARCH ENGINE!! RUN THE CELL”. To choose the score type, select 1 or 2. 1 is for tf-idf score and 2 for our score. The top 20 tweets will show according to the query.

** Subsection RQ1.ipynb ** - Import df_tweets.csv.
  In question b) run all cells, specified functions:
    · ** create_index_tfidf() ** to create the inverted index of the tweets.
    · ** rankDocuments() ** to generate the ranking of tf idf of the tweets.
    · ** search_tf_idf() ** to look for the query string in the keys of the index dictionary and proceed to create the ranking.
    · INPUT: Write queries.
   
  In question c) run all cells, specified functions:
    · ** get_embedding_w2v() ** return tweet2vec representation.
    · ** create_index_w2v() ** create index for word2vec.
    · ** rankDocuments_w2v() ** rank tweets according to the given query following word2vec values.
    · ** search_w2t() ** to look for the query string in the keys of the index dictionary and proceed to create the ranking.
    · INPUT: Write queries.
