```
# **Vision Transformer (ViT) from "An Image is Worth 16x16 Words"** 🖼️✨

This repository contains my implementation of the **Vision Transformer** (ViT) model based on the groundbreaking paper,
**"An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"** by Dosovitskiy et al. 2020. 📜🚀

---

## What's Inside? 📦🤓

I've recreated the core components of the ViT architecture from scratch, including:

* **Patch Embedding:** 🧩 Splitting an image into fixed-size patches and linearly embedding them. Think of it like turning an image into a sequence of "words"!
* **Position Embeddings:** 📍 Adding positional information to the patches so the model knows where each one came from. No more confusion!
* **Transformer Encoder:** 🤖 The star of the show! A series of Transformer blocks with multi-head self-attention and a feed-forward network to process the sequence of patch embeddings.
* **Classification Head:** 🧠 A simple MLP head on top of the final representation to make a classification prediction.

---

## Why I Built This? 🤔💻

I wanted to dive deep into the mechanics of this incredible paper and truly understand how ViT works under the hood. It was a fascinating challenge to translate the concepts from the paper into a working codebase. This project served as a perfect way to solidify my understanding of Transformer architectures beyond just natural language processing. 🧠💡

---

