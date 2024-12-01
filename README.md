# TextGenSerbia
This project aims to build a special GPT model just for the Serbian language. It will have a tool to break up text into smaller parts (called SentencePiece) and a script to train the model from the beginning using PyTorch. The training will use Serbian text taken from a collection of books.

trainSentencepiece.py: This script prepares the data and trains a tokenizer using SentencePiece. It creates a tokenizer model that will be used to tokenize text into tokens tailored for the corpus.

train.py: Main script for training GPT. This script defines the model architecture and hyperparameters, trains the model on the custom corpus, and allows for text generation with the trained model. It generates text character by character, which will be highly customized based on the given sequence.
