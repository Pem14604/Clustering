# Text Clustering


# Steps
1 Data Prepprocessing- punchuation removal, stopwords removal, special character, digit and other words we dont want as per our usecase.
2 Text to vector conversion- TDIDF, Word2Vec, Glove, Fasttext
3 Clustering- Kmeans, Gausian, H-cluster/Agglo, Lingo.
4 Representation- we can try different graphs like Foamtree, Nextworx, Neo4j

- Foamtree-https://carrotsearch.com/foamtree/
- Netowrkx-https://networkx.github.io/
- Neo4j-https://neo4j.com/
 
 
 # Text to vector conversion

I have tried various techniquesas our result is depend on our vector, how good our text is represneted in vector.
Got best result with TFIDF and Fasttext. Even i have tried varies tweeking techniaues in TDIDF like keeping only nous and verbs in
feature vector, setting threshold to keep the vector size upto a limit and various combination of max_df and min_df, it all depend on our
data and you need to test various combination of these to get the best results.

# Code is uploaded for different steps.

-	Data cleaning-punctiuation removal,stopwords,digits, special character,Keeping only English words
- Text to Vector or word embedding’s: Fasttext, TFIDF,Word2vec,TFIDF tweeking by setting threshold
- Fastetxt transfer learning or over the top training
- Sentence vector
- Algo: Kmeans, Agglomerative
- Dataframe
   
