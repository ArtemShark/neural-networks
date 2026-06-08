# Artificial Neural Networks

Labs from the "Artificial Neural Networks" course at Warsaw University of Technology. Covers the full deep learning stack from feedforward networks to transformers, using both PyTorch and TensorFlow.

## Labs

### 1. Time Series Forecasting (PyTorch)

Electricity consumption prediction using feedforward neural networks. Sliding window approach (96-step window = 24 hours at 15-min intervals), hyperparameter grid search, and year-long recursive forecasting.

### 2. Image Classification (PyTorch)

CNN-based image classification with custom architectures and ResNet18 transfer learning. Includes data augmentation, batch normalization, dropout tuning, and model comparison across configurations.

### 3. NLP Pipeline (TensorFlow/Keras + spaCy)

End-to-end NLP on Project Gutenberg books:
- Text cleaning, tokenization, stopword filtering
- Vectorization: Bag-of-Words, TF-IDF, Word2Vec
- Named Entity Recognition with spaCy
- Character-level text generation (Simple RNN)
- Text classification (LSTM)
- Word-level text generation (GRU)

### 4. Transformers from Scratch (PyTorch)

Building transformer components step by step:
- Input embeddings and positional encoding
- Multi-head self-attention mechanism
- Encoder-only transformer (BERT-style)
- Decoder-only transformer with causal masking (GPT-style)
- API integration with GPT-4o, Claude, Gemini, and Grok

## Tech

PyTorch, TensorFlow/Keras, spaCy, NLTK, NumPy, pandas, Matplotlib
