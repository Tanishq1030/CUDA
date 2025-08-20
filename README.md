# CUDA Experiments 🚀

This repository contains simple CUDA programs for learning and experimenting with GPU programming.  
All examples are tested on **Google Colab** using a free NVIDIA T4 GPU.

---

## 📦 Requirements
- [Google Colab](https://colab.research.google.com/) (with GPU enabled)
- CUDA Toolkit (pre-installed on Colab)
- `nvcc` compiler

---

## ▶️ Running the code
1. Open this repo in Google Colab.
2. Create a `.cu` file (example: `vector_add.cu`).
3. Compile using:
   ```bash
   !nvcc vector_add.cu -o vector_add
