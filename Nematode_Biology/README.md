The dataset contains a collection of research papers of **nematode biology** with attributes like title,authors,citations and abstracts.  
We have used **title and abstract** as the final text data to be used by topic modelling algorithms to classify into topics   
We have first tried *LDA* on the whole dataset for a random value of k(=10 here) and found its coherance and perplexity score. Then we have plotted a graph of coherance value by using different values of K for the whole dataset.  
For the **most optimum K** found,we have represented the topics in terms of their wordclouds  
Then we have proceeded to **get random samples of the dataset(random subset containing only 80% of data from dataset) EACH** and for different values of K,proceeded to plot a graph of coherance score for each sample of the dataset. This final step has been done to find the optimum value of K that actually fits the dataset in actuality. 
Next task would be to implement the research paper provided  
The dataset used:https://github.com/tdhopper/topic-modeling-datasets/tree/master/data/raw/Nematode%20biology%20abstracts
