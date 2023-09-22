# CBOW_Feedforward_Neural_Network

Train word embeddings using the continuous-bag-of-words (CBOW) method.
We define a simple feed-forward neural network that takes in a context vector and predicts the word that completes the context. 

- We use WikiText-2, a corpus of high-quality Wikipedia articles.

- We use dense word embeddings based on the word2vec paradigm. In particular, we use the continuous-bag-of-words approach, which trains a model to predict a word based on the embeddings of surrounding words. For example, in the sentence "the man walks the dog in the park", the embeddings for the words ("man, "walks", "dog", "in") will be used to predict the word "the" (if your context size is 2 on each side of the target word).
