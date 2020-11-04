# Sentiment Analysis for Review Rating Prediction
## Pipeline
- Data Loader: Load data from disks
  - Tokenization/Stemmed Words/N-gram/Filter stopwords
  - Feature Dictionary
- Feature Extraction: Find useful features
  - Word2Vec skip-gram model with 300 dimensions is trained with the word tokens from dataset
- Classification: 
  - biLSTM-CNN:
  The configuration provides an informative representation of the sequential structure of sentences as the bi-LSTM layer acts like an encoder for each token while CNN extracts local features with richer representation of the original input. 
