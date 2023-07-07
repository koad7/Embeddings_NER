# Embeddings_NER

This project focuses on building the code described in this paper:  [Named Entity Recognition Only from Word Embeddings](https://aclanthology.org/2020.emnlp-main.723/).


## Named Entity Recognition Only from Word Embeddings

*Ying Luo, Hai Zhao, Junlang Zhan*

### Abstract
Deep neural network models have helped named entity recognition achieve amazing performance without handcrafting features. However, existing systems require large amounts of human annotated training data. Efforts have been made to replace human annotations with external knowledge (e.g., NE dictionary, part-of-speech tags), while it is another challenge to obtain such effective resources. In this work, we propose a fully unsupervised NE recognition model which only needs to take informative clues from pre-trained word embeddings.We first apply Gaussian Hidden Markov Model and Deep Autoencoding Gaussian Mixture Model on word embeddings for entity span detection and type prediction, and then further design an instance selector based on reinforcement learning to distinguish positive sentences from noisy sentences and then refine these coarse-grained annotations through neural networks. Extensive experiments on two CoNLL benchmark NER datasets (CoNLL-2003 English dataset and CoNLL-2002 Spanish dataset) demonstrate that our proposed light NE recognition model achieves remarkable performance without using any annotated lexicon or corpus.
