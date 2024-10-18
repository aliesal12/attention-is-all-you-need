# Attention is All You Need
This repository contains three implementations of the seminal "Attention Is All You Need" paper by Vaswani et al., 2017. The paper introduced the Transformer model, which has since become foundational in the field of Natural Language Processing (NLP). This project demonstrates the same Transformer architecture implemented using three different methods:

1. From Scratch (NumPy) - A pure Python implementation using only NumPy, handling forward and backward propagation, gradient calculations, and weight adjustments manually.
2. PyTorch - An implementation using the PyTorch deep learning framework for easier tensor manipulation and autograd functionality.
3. TensorFlow - An implementation using TensorFlow with a focus on leveraging its high-level APIs for building the Transformer model.

## Table of Contents
- Project Overview
- Implementations
  - NumPy
  - PyTorch
  - TensorFlow
- References

## Project Overview
The Transformer model, introduced by Vaswani et al., 2017, eliminated the need for recurrence and convolution in sequence transduction models by relying entirely on the self-attention mechanism. This repository demonstrates the model built in three ways:
1. Custom NumPy-based implementation: This provides a deep dive into how every component of the transformer (attention, feed-forward layers, optimizers, etc.) works behind the scenes.
2. PyTorch implementation: Uses PyTorch to simplify building and training, taking advantage of its dynamic computation graph and autograd feature.
3. TensorFlow implementation: Uses TensorFlow's high-level APIs to efficiently build and train the Transformer model.

## Implementations
### NumPy Implementation
- Objective: Manually create each part of the Transformer model from scratch, including the attention mechanism, positional encodings, layer normalization, feed-forward layers, and the Adam optimizer.
- Features:
  - Fully custom forward and backward propagation
  - Gradient calculations done manually
  - Weight updates handled by a custom Adam optimizer
### PyTorch Implementation
- Objective: Build the Transformer model using PyTorch for automatic differentiation and a more intuitive tensor manipulation experience.
- Features:
  - Uses PyTorch's autograd for automatic gradient computation
  - Modular and flexible, with reusable components for training on various datasets
### TensorFlow Implementation
- Objective: Implement the Transformer using TensorFlow, leveraging its eager execution and high-level API (Keras) to simplify model building and deployment.
- Features:
  - Optimized for training and inference with TensorFlow
  - Uses Keras for cleaner and more modular code

## References
Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is All You Need. Advances in neural information processing systems, 30.

##
Feel free to explore each folder and try out the implementations yourself. If you have any suggestions, improvements, or questions, please feel free to open an issue or submit a pull request!
