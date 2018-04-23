# SentimentClassifierCNN

This projects uses the sentiment-labeled Stanford Treebank dataset as training data for a CNN-based sentiment classifier. The output is rated from 0-4, where 0 indicates the most negative sentiment and 4 indicates the most positive sentiment. On running, there is the option to use glove, word2vec, or both glove+word2vec (via multichannel) inputs into the CNN. There is also the option to use these pretrained inputs as simply frozen inputs, or as initializations subject to training themselves. Used PyTorch wrappers to make compatible with GPUs. 

Implemented the architecture I found in this paper: http://aclweb.org/anthology/D14-1181
