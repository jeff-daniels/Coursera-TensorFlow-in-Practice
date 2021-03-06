# Natural Language Processing in TensorFlow  

## Exercise 1-Explore the BBC News Archive  
The BBC News Archive is a csv file with a row for each article.  Each row has a label for the article topic and also the article.  Stopwords were removed, the dataset tokenized, and all the articles and labels were converted to these tokens.  
- [Using APIs](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%201%20-%20Lesson%201.ipynb)  
- [Padding](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%201%20-%20Lesson%202.ipynb)  
- [News Headlines Dataset for Sarcasm Detection](https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection/home)  
- [Sarcasm Detection](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%201%20-%20Lesson%203.ipynb)  
- [BBC Text Archive](http://mlg.ucd.ie/datasets/bbc.html)  
- [Stop Words](https://github.com/Yoast/YoastSEO.js/blob/develop/src/config/stopwords.js)  
## Exercise 2-BBC News Archive  
Building upon the previous exercise, the BBC News Archive was used to train a model to classify the article topics.  Key features of this model include an embedding layer and global average pooling layer.  The embedding layer values were used to create vectors of the vocabulary that could be viewed on an [Embedding Projector](https://projector.tensorflow.org/).  There, the words are represented in a 3 dimension space where words with similar vectors are shown close to eachother.  
- [IMDB Reviews Dataset](http://ai.stanford.edu/~amaas/data/sentiment/)  
- [Visualizing Embeddings on the IMDB Dataset](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%202%20-%20Lesson%201.ipynb)  
- [Embeddings on the Sarcasm Dataset](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%202%20-%20Lesson%202.ipynb)  
- [Subwords on the IMDB Dataset](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%202%20-%20Lesson%203.ipynb)  
## Exercise 3-Exploring Overfitting in NLP  
A sentiment classifier was built using a model with an LSTM layer combined with 1D convolutional and max pooling layers.  A dropout layer was also used in an attempt to reduce overfitting.  The dataset was [Sentiment140 Dataset](https://www.kaggle.com/kazanova/sentiment140).  The [GloVe Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/) was used as a pre-trained embedding layer.  
- [IMDB Subwords 8K with Single Layer LSTM](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%201a.ipynb)  
- [IMDB Subwords 8K with Multi Layer LSTM](https://github.com/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%201b.ipynb)  
- [IMDB Subwords 8K with 1D Convolutional Layer](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%201c.ipynb)  
- [IMDB Reviews with GRU (and optional LSTM and Conv1D)](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%202d.ipynb#scrollTo=nHGYuU4jPYaj)  
- [Sarcasm with Bidirectional LSTM](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%202.ipynb#scrollTo=g9DC6dmLF8DC)  
- [Sarcasm with 1D Convolutional Layer](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%203%20-%20Lesson%202c.ipynb#scrollTo=g9DC6dmLF8DC)  
## Exercise 4-Using LSTMs, see if you can write Shakespeare!  
A dataset of sonnets was used to train an RNN model.  The model layers contain an embedding layer, two-layer LSTM with dropout, and a dense layer that uses regularization.  
- [Poetry Generator](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%204%20-%20Lesson%201%20-%20Notebook.ipynb)  
- [Poetry Generator on Larger Dataset](https://github/lmoroney/dlaicourse/blob/master/TensorFlow%20In%20Practice/Course%203%20-%20NLP/Course%203%20-%20Week%204%20-%20Lesson%202%20-%20Notebook.ipynb#scrollTo=Ww-QdMf4pfS_)
- [Generating text using a character-based RNN](https://www.tensorflow.org/tutorials/text/text_generation)  


