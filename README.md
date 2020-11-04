# Sentiment Analysis for Review Rating Prediction
## Pipeline
- Data Loader: Load data from disks
  - Tokenization/Stemmed Words/N-gram/Filter stopwords
  - Feature Dictionary
- Feature Extraction: Find useful features
  - Word2Vec skip-gram model with 300 dimensions is trained with the word tokens from dataset
- Classification: 
  - biLSTM
