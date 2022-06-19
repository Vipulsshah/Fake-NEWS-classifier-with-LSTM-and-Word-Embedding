# Fake-NEWS-classifier-with-LSTM-and-Word-Embedding
# Solution:
1) preprocessed the dataset using NLTK and re Libraries to remove punctuation, lowernimg the word.
2) Applyed  Porter Stemmer technique to after removing Stopwords form the sentences.
3) Used One-Hot encoding with pad_sequences to convert Test NEWS Titles into feature vectors.
4) Used LSTM RNN technique to get the maximum accuracy.
5) Built the Model using Word Embedding layer to get the feature matrix.
6) Used LSTM, Dropout and Dense layers to build a Sequential Model.
7)Got the Train accuracy of 98%, validation accuracy of 92% and Test accuracy of 91.89%.
