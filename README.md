# NLP Text Preprocessing & Feature Extraction Workshop

A comprehensive collection of Jupyter notebooks demonstrating essential Natural Language Processing (NLP) techniques for text preprocessing and feature extraction. Perfect for beginners and intermediate practitioners looking to master text data preparation for machine learning models.

## Topics Covered

### Part 1: Text Preprocessing (IMDB Dataset)
- **Data Loading**: Multiple methods (Google Drive, Kaggle API, direct download)
- **Text Cleaning**:
  - Lowercasing & Punctuation removal
  - HTML tag & URL removal
  - Emoji handling (regex & emoji library)
  - Chat shortform conversion (ASAP → As Soon As Possible)
  - Spelling correction with TextBlob
- **Tokenization**:
  - Split function (limitations)
  - Regular expressions
  - NLTK tokenizers (word_tokenize, sent_tokenize)
  - spaCy tokenization
- **Normalization**:
  - Stemming (PorterStemmer) - fast but aggressive
  - Lemmatization (WordNetLemmatizer) - slower but accurate
- **Stopword Removal**: NLTK stopwords corpus

### Part 2: Feature Extraction
- **Bag of Words (BoW)**: CountVectorizer implementation
- **N-grams**: Unigrams, bigrams, and trigrams
- **TF-IDF**: Term Frequency-Inverse Document Frequency
- **Advanced Embeddings**: References to Word2Vec, GloVe, FastText

### Part 3: Advance 
 1. **Word2vector** : https://colab.research.google.com/drive/1tzN3fLysDmGUVT_tk5iZNzo8dusrhvXh?usp=sharing
 2. **Glove** : https://colab.research.google.com/drive/1PzlX4H5R1wrUbRbL8xHWLINNJNfZR-vI?usp=sharing
 3. **FastText** : https://colab.research.google.com/drive/1yQ3NPbzJoiOKb2ic8RNBecvwWkaeC5Sn?usp=sharing

## Installation
  git clone https://github.com/yourusername/nlp-preprocessing-workshop.git
  cd nlp-preprocessing-workshop


# Install dependencies
pip install pandas numpy nltk spacy textblob scikit-learn kagglehub
python -m spacy download en_core_web_sm
python -m nltk.downloader all
