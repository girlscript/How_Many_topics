# Topic Modeling on Newsgroup dataset 
---
  ## About the 20newsgroup dataset:
It is a collection of newsgroup documents based on 20 different topics. It is a popularly used dataset for NLP purposes like topic modelling and text classification. The dataset can be found in the **scikit-learn** library of python. It is a collection of roughly 20,000 newsgroup documents split into 2 parts: the *training dataset* and the *test dataset*. 
<br/>The 20 newsgroups are:
* alt.atheism
* comp.graphics
* comp.os.ms-windows.misc
* comp.sys.ibm.pc.hardware
* comp.sys.mac.hardware
* comp.windows.x rec.autos
* misc.forsale talk.politics.misc
* rec.motorcycles
* rec.sport.baseball
* rec.sport.hockey sci.crypt
* sci.electronics
* sci.med
* sci.space
* soc.religion.christian
* talk.politics.guns
* talk.politics.mideast talk.religion.misc

The dataset can be downloaded from **Kaggle** also: [20 Newsgroups](https://www.kaggle.com/crawford/20-newsgroups "20 Newsgroups")

---
  ## Topic Modelling
**Topic Modelling** is a popular unsupervised NLP technique to identify the number of topics in a corpus (huge dataset of text elements). There are various algorithms developed for the purpose of Topic Modelling:
* Latent Semantic Analysis (LSA)
* Latent Dirichlet Allocation (LDA)
* Non-negative Matrix Factorization (NFM)...

---
  ## What we did?
We have been able to implement LSA and LDA algorithms on the dataset.
  ### LSA Implementation
LSA implemtation gave us promising results with the value of k between **25 to 30**.
  ### LDA Implementation
LDA implementation gave us good results:<br/>
* Perplexity = -8.602970553126184
* Coherence Score = 0.5578795935507215 

---
## REFERENCES
* LSA model:
  ---
  * https://www.datacamp.com/community/tutorials/discovering-hidden-topics-python
  * https://www.analyticssteps.com/blogs/introduction-latent-semantic-analysis-lsa-and-latent-dirichlet-allocation-lda
  * https://towardsdatascience.com/latent-semantic-analysis-sentiment-classification-with-python-5f657346f6a3
  * https://www.analyticsvidhya.com/blog/2018/10/stepwise-guide-topic-modeling-latent-semantic-analysis/
  * https://www.kaggle.com/rcushen/topic-modelling-with-lsa-and-lda
  
  ---
* LDA model:
  ---
  * https://www.tutorialspoint.com/gensim/gensim_creating_lda_mallet_model.htm
  * https://programminghistorian.org/en/lessons/topic-modeling-and-mallet
  * https://medium.com/analytics-vidhya/how-to-perform-topic-modeling-using-mallet-abc43916560f

  ---
 * Topic Modeling:
 ---
 * http://derekgreene.com/papers/greene14topics.pdf
