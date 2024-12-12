# ***REAN*** - Reccurent Embedding Approximation Network

## Overview

Traditional language models generate text by predicting the next token in a sequence. This typically involves predicting a probability distribution over the vocabulary.

REAN takes a different approach, directly predicting the embedding of the next token. 

### Potential Advantages:
* **Lower Model Complexity**: By directly predicting embeddings, the model can be smaller and faster.
* **Enhanced Flexibility**: Embeddings can capture semantic and syntactic information, potentially leading to more creative and coherent text generation.

### Key Challenges and Limitations:
* **Dependency on External Word Embeddings**: REAN relies on a pre-trained word embedding model, adding an additional layer of complexity and potentially limiting its performance.
* **Current Performance**: While promising in theory, REAN's current implementation still exhibits suboptimal performance compared to state-of-the-art language models.

## Getting Started

### Running the model:
* Load pre-trained REAN model and the corresponding word embedding model.
* Configure and execute the `run_model.ipynb` notebook to generate text.

### Training REAN model:
* Load word embedding model and the plaintext dataset.
* Configure and execute the `train_REAN.ipynb` notebook to train and test the model.
