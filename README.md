Next-Character Prediction: From Bigram to Transformers
Overview
This project explores different models for next-character prediction, starting from simple statistical approaches and progressing to deep learning architectures. The goal is to analyze how model complexity impacts accuracy in predicting the next character in a sequence.

Models Implemented
Bigram Model – Counts character transitions and builds a probability distribution.
Neural Networks – Uses embeddings and optimizations to improve predictions.
Multi-Layer Perceptron (MLP) – Introduces hidden layers for better learning.
Gated Recurrent Unit (GRU) – Captures sequential dependencies using memory.
Transformer – Leverages attention mechanisms for state-of-the-art performance.
Bigram Model Implementation
Created a (27x27) matrix to map letter transitions, including start and end tokens.
Converted counts into a probability distribution for next-character prediction.
Used maximum likelihood estimation to optimize the model.
Achieved a negative loss of ~2.45, which is reasonable for a simple model.
Next Steps
Implement Neural Networks to improve accuracy.
Optimize training and analyze probability distributions.
Compare results across all models to understand improvements in performance.
How to Use
Clone the repository.
Install dependencies (torch, numpy, etc.).
Run the bigram_model.py script to train and test the Bigram model.
Follow the upcoming implementations for deeper models.
Stay Updated
This project is evolving as I implement new models. Follow along to see how accuracy improves with more advanced techniques! 🚀
