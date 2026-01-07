
# Neural Network with Attention Mechanisms and t-SNE

This project demonstrates how attention mechanisms in neural networks can be interpreted and visualized using t-SNE (t-Distributed Stochastic Neighbour Embedding). The focus is on understanding how neural models assign importance to different parts of input data, particularly in natural language processing tasks.

## Project Motivation
Neural networks often behave as black boxes, making it difficult to understand *why* a model makes a particular prediction. Attention mechanisms address this by allowing the model to focus on the most relevant parts of the input. However, attention weights themselves can still be abstract.

This project combines **attention mechanisms** with **t-SNE visualization** to make model behaviour more interpretable and intuitive.

## Key Concepts Covered
- Neural Networks and layered representations
- Attention mechanisms in sequence models
- Encoder–Decoder architecture
- Limitations of traditional RNNs (bottleneck problem, vanishing gradients)
- Visual interpretation of attention weights
- Dimensionality reduction using t-SNE

## Attention Mechanism Overview
Attention allows a model to dynamically weight different parts of an input sequence rather than relying on a single compressed context vector. This approach:
- Reduces information loss in long sequences
- Improves performance on sequence-to-sequence tasks
- Aligns more closely with how humans process language

## Dataset
- **Twitter Sentiment140 Dataset**
- Contains approximately **1.6 million tweets**
- Labels represent sentiment polarity
- Source: Kaggle

## Objective
- Train a neural network with an attention mechanism for sentiment analysis
- Extract and analyze attention weights
- Use t-SNE to visualize how attention-weighted representations cluster in lower-dimensional space
- Understand which words or patterns influence sentiment predictions

## Methodology
- Preprocess raw tweet text
- Train a neural network with an attention layer
- Extract learned attention representations
- Apply t-SNE for non-linear dimensionality reduction
- Visualize attention-driven embeddings

## Visualization
t-SNE is used to project high-dimensional attention-weighted features into two dimensions, allowing:
- Exploration of semantic clustering
- Inspection of sentiment-driven separation
- Improved interpretability of neural representations

## Results & Insights
- Attention mechanisms highlight sentiment-bearing words more effectively
- t-SNE visualizations reveal meaningful clustering patterns
- The approach bridges model performance with interpretability
- Demonstrates how attention can be inspected beyond accuracy metrics

## Tools & Technologies
- Python
- Neural Networks (Attention-based models)
- t-SNE
- NLP preprocessing
- Matplotlib / Seaborn
- Jupyter Notebook

## Project Structure
- notebooks/ – Model training and visualization notebooks
- slides/ – Conceptual explanations and theory
- README.md – Project overview

## References
- https://theaisummer.com/attention/
- https://www.datacamp.com/tutorial/introduction-t-sne
- https://www.kaggle.com/datasets/kazanova/sentiment140

## Author
Samara Naeem
