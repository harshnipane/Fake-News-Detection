# Fake-News-Detection
Project is based on analysis and classification of news using an LSTM (Long Short Term Memory) - Recurrent Neural Network to Identify fake news over a text-based news stream.
Aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.
## Text Preprocessing
- Natural language processors (NLP) work by converting words (text) into numbers. These numbers are then used to train an Al/ML models to make predictions.
- Tokenization(NLTK) is the first step in any NLP pipeline. A tokenizer breaks unstructured data and natural language text into chunks of information that can be considered as discrete elements.
- Lemmatization is a technique that switches any kind of a word to its base root mode. Lemmatization is responsible for grouping different inflected forms of words into the root form, having the same meaning.
## Word vector encoding
- In one hot encoding, every word (even symbols) which are part of the given text data are written in the form of vectors, constituting only of 1 and 0.
- pad_sequences is used to ensure that all sequences in a list have the same length. By default this is done by padding 0 in the beginning of each sequence until each sequence has the same length as the longest sequence.
## Model
- A Sequential model is appropriate for a plain stack of layers where each layer has exactly one input tensor and one output tensor.
- LSTM is a recurrent neural network (RNN) architecture that REMEMBERS values over arbitrary intervals. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration. Relative insensitivity to gap length gives an advantage to LSTM over alternative RNNs, hidden Markov models and other sequence learning methods.
