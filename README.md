# MiniLlama 

MiniLlama is an educational implementation of a modern Transformer language model (Llama-style) built from scratch using PyTorch.

This project demonstrates how to implement state-of-the-art LLM features manually, without relying on high-level libraries like Hugging Face Transformers.

## Key Features

- **RoPE (Rotary Positional Embeddings):** Modern positional encoding replacing absolute embeddings.
- **RMSNorm (Root Mean Square Normalization):** Pre-normalization for better training stability.
- **SwiGLU Activation:** A variant of GLU using the Swish activation function.
- **Grouped Query Attention (GQA):** Optimized attention mechanism for faster inference.
- **KV-Cache:** Efficient inference by caching Key and Value states.
