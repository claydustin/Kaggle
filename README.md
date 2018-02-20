# Kaggle

Kernel for Kaggle TedTalk Competition: https://www.kaggle.com/rounakbanik/ted-talks

ted_recommendations.py 
-performs basic EDA
-Uses Doc2Vec representations of Ted transcripts to recommend similar Ted Talks
  >Conclusion is that Doc2Vec recommendations are preferred to Ted provided recs
  
ted_nbsvm.py
-Motivated by NBSVM: https://nlp.stanford.edu/pubs/sidaw12_simple_sentiment.pdf
-creates Tfidf features of transcripts
-Uses Tfidf and Talk ratings to create a posterior distribution under Naive Bayes assumption
-Tfidf feature doesn't add much explanatory information to the model. Because Tfidf is a method for topic labelling the conclusion is that the talk's topic does not influence its rating.
  
