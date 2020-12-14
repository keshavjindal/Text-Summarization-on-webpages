# Text-Summarization-on-webpages
In this Notebook, we have tried to implement **Text Summarisation** using **Natural Language Processing(NLP)**. This can be used to summarise various articles, reviews, news reports available on different webpages. The text to be summarised is taken from various webpages by using Web Scrapping.

There are two types of Text Summarisation techniques:
1. **Extractive Text Summarisation** : It is a method to find the most informative sentences within a large body of text which are used to form a summary.
2. **Abstractive Text Summarisaton** : It is a method to generate concise phrases that are semantically consistent with the large body of text.

We will implement Extractive Text Summarisation in this Notebook.

This notebook contains Text Summarisation based on two Scoring methods namely:
1. **Tf-idf Scoring Method** : Tf-idf stands for "Term Frequency - Inverse Document Frequency". Tf-idf weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. We have used this weight to get the importance of each sentence in our Text material.
2. **Word Embeddings and PageRank Scoring Method** : Word Embeddings are a method to convert language words into a vector form to apply various mathematical functions on them to extract various features of words. Using Word Embeddings, we will evaluate Cosine Similarity of Sentences and pass it on the PageRank Algorithm. Finally, we will implement TextRank Algorithm.

The second method is implemented using **Google's Word2Vec** and **Stanford's Glove** word embeddings.

Finally, an **All in One Model** is implemented by combining the two methods above mentioned.
