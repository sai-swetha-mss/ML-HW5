# ML-HW5
#Sai Swetha Manuguri #700770652
Question 1. Transformer Attention & Encoder Block – Implementation
This repository contains two fundamental implementations related to the Transformer architecture:
Scaled Dot-Product Attention (NumPy)
Simple Transformer Encoder Block (PyTorch)
These implementations are educational, clean, and optimized for clarity — ideal for students, researchers, and anyone learning Transformers from scratch.
1. Scaled Dot-Product Attention (NumPy)
Overview
Scaled dot-product attention is the core operation inside every Transformer model.
Features
Fully NumPy-based
Includes score scaling
Stable softmax implementation
Returns both attention weights and the context vector

Question 2. Simple Transformer Encoder Block (PyTorch)
Overview
This is a clean implementation of a simplified Transformer encoder block containing:
✔ Multi-Head Self-Attention
✔ Feed-Forward Network (FFN)
✔ Residual Connections
✔ Layer Normalization
Model Architecture
Input
  ↓
Multi-Head Self-Attention
  ↓ (Add & Norm)
Feed-Forward Network
  ↓ (Add & Norm)
Output
