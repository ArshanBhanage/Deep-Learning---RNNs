# 🧠 Deep Learning — RNNs, Transformers & Graphs

> **Assignment:** Execute and explain Google Colab notebooks covering Recurrent Neural Networks, NLP, Vision Transformers, and Graph Neural Networks. Each colab is archived with full outputs and explained in a dedicated YouTube video.

---

## 📁 Repository Structure

```
Deep-Learning---RNNs/
│
├── 01_RNN_LSTM/
│   └── RNN_LSTM_Colab.ipynb          # Executed with outputs
│
├── 02_NLP_DeepLearning/
│   └── NLP_Colab.ipynb               # Executed with outputs
│
├── 03_Vision_Transformers/
│   └── Vision_Transformer_Colab.ipynb  # Executed with outputs
│
├── 04_Graph_Transformers/
│   └── Graph_Transformer_Colab.ipynb   # Executed with outputs
│
└── README.md
```

---

## 🎥 Video Walkthroughs

Each video is a **45–60 second** walkthrough of the colab, explaining every code block and output.

| # | Colab | Topic | YouTube Video |
|---|-------|-------|---------------|
| 1 | RNN & LSTM | Sequence modeling, vanishing gradients, LSTM gates | [▶ Watch Video](#) |
| 2 | NLP Deep Learning | Text tokenization, embeddings, LSTM text classifier | [▶ Watch Video](#) |
| 3 | Vision Transformers | Image patches, positional encoding, self-attention for vision | [▶ Watch Video](#) |
| 4 | Graph Transformers | Message passing, GNNs, attention on graph structure | [▶ Watch Video](#) |

> 🔗 **Replace each `[▶ Watch Video](#)` link with your actual YouTube video URL after uploading.**

---

## 📓 Colab Notebooks

| # | Colab | Original Link | GitHub (with outputs) |
|---|-------|---------------|----------------------|
| 1 | RNN & LSTM | [Open in Colab](https://colab.research.google.com/drive/1uGPf1pUz_P0JIlpBqcPOJyHikmvO8uV2) | [View Notebook](./01_RNN_LSTM/RNN_LSTM_Colab.ipynb) |
| 2 | NLP Deep Learning | [Open in Colab](https://colab.research.google.com/drive/129nxLYowmTdGpQGziABOYs7FpRqQmNsF) | [View Notebook](./02_NLP_DeepLearning/NLP_Colab.ipynb) |
| 3 | Vision Transformers | [Open in Colab](https://colab.research.google.com/drive/1IQp0RU4w7DXRKlLITyYgYFLMntFvrvdx) | [View Notebook](./03_Vision_Transformers/Vision_Transformer_Colab.ipynb) |
| 4 | Graph Transformers | [Open in Colab](#) | [View Notebook](./04_Graph_Transformers/Graph_Transformer_Colab.ipynb) |

---

## 🧪 What's Inside Each Colab

### 1. 🔁 RNN & LSTM — Sequence Modeling
**Concepts covered:**
- What makes sequential data different (order matters)
- Building a SimpleRNN in Keras with `return_sequences=True`
- The vanishing gradient problem and why it breaks plain RNNs
- LSTM architecture: cell state, input gate, forget gate, output gate
- Comparing RNN vs. LSTM performance on the same task
- Plotting training/validation accuracy curves

**Key output:** LSTM achieves lower loss than SimpleRNN, demonstrating its ability to capture longer-range dependencies.

---

### 2. 📝 NLP with Deep Learning — Text Classification
**Concepts covered:**
- Text preprocessing: tokenization with Keras `Tokenizer`
- Padding sequences to uniform length with `pad_sequences`
- Word embeddings: mapping tokens to dense vectors
- Building an Embedding → LSTM → Dropout → Dense classifier
- Training on a sentiment/text classification dataset
- Making predictions on new sentences

**Key output:** ~85–90% validation accuracy on the text classification task.

---

### 3. 👁️ Vision Transformers (ViT)
**Concepts covered:**
- Why transformers moved from NLP to vision
- Splitting images into fixed-size patches (e.g., 16×16)
- Flattening patches into sequences + adding positional embeddings
- Multi-head self-attention for global image understanding
- Comparing ViT attention maps to CNN feature maps
- Training ViT on an image classification benchmark

**Key output:** Attention heatmaps showing the model focusing on the relevant object region.

---

### 4. 🕸️ Graph Neural Networks & Graph Transformers
**Concepts covered:**
- Why standard NNs fail on graph-structured data
- Representing graphs with adjacency and feature matrices
- Message passing: aggregating neighbor features iteratively
- Graph Transformer: adding attention weights to message passing
- Node classification and graph classification tasks
- Visualizing learned graph embeddings

**Key output:** Accurate node/graph classification with visualization of learned cluster structure.

---

## 🛠️ How to Run

1. Click any **"Open in Colab"** link above
2. Go to **File → Save a copy in Drive** to get your own editable copy
3. Run all cells top to bottom (**Runtime → Run all**)
4. After execution, download and push to your fork of this repo

---

## 📚 Learning Resources

- [Illustrated RNN/LSTM by Jay Alammar](https://jalammar.github.io/illustrated-rnn/)
- [Attention Is All You Need (original paper)](https://arxiv.org/abs/1706.03762)
- [An Image is Worth 16x16 Words — ViT paper](https://arxiv.org/abs/2010.11929)
- [A Gentle Introduction to Graph Neural Networks](https://distill.pub/2021/gnn-intro/)

---

## 👤 Author

**Arshan Bhanage**  
Deep Learning Portfolio Assignment — RNNs, Transformers & Graphs  

[![GitHub](https://img.shields.io/badge/GitHub-ArshanBhanage-black?logo=github)](https://github.com/ArshanBhanage)

---

*All notebooks executed with full outputs archived. Videos recorded as per assignment guidelines.*
