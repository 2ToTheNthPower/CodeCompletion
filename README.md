# CodeCompletion
Using n-grams, LSTMs, and Transformers to predict the next word/char in a code sequence (using the IBM CodeNet dataset)

# Goals:
The goal of this project is to replicate existing work done for code completion using n-gram models and machine learning methods.  
We started by training word embeddings using the accepted Python code samples from the IBM CodeNet dataset.  The reason we trained our own word embeddings
rather than using existing pre-trained word embeddings is that words in code may be used differently than word in normal NLP tasks.
Training our own word embeddings allows us to capture those differences.
