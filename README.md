# Advanced Learning for Text and Graph Data (ALTEGRAD) — M2 MVA

[![Course: M2 MVA](https://img.shields.io/badge/Master-M2%20MVA%20ENS%20Paris--Saclay-blue.svg)](https://www.master-mva.com/)
[![Institution: École Polytechnique](https://img.shields.io/badge/Institution-%C3%89cole%20Polytechnique-red.svg)](https://www.polytechnique.edu/)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/framework-PyTorch-orange.svg)](https://pytorch.org/)

Coursework implementations, laboratory assignments, and theoretical study guides for the **Advanced Learning for Text and Graph Data (ALTEGRAD)** graduate course at **École Normale Supérieure Paris-Saclay (Master MVA)** and **École Polytechnique**.

---

## 📚 Curriculum & Laboratory Modules

| Module | Topic | Core Methods & Architectures |
|---|---|---|
| **Lab 1** | Neural Machine Translation (NMT) | Seq2Seq, Bidirectional LSTM encoders, Global Bahdanau / Luong Attention mechanisms, Beam Search decoding |
| **Lab 2** | Pretrained Transformers & LLM Adaptation | Decoder-only Transformer architectures, Parameter-Efficient Fine-Tuning (PEFT, LoRA), causal language modeling, perplexity evaluation |
| **Lab 3** | Graph Neural Networks & Node Classification | Message passing neural networks (MPNNs), GCN, GAT (Graph Attention), GraphSAGE, spectral graph theory |

---

## 🛠️ Environment & Setup

To reproduce the notebook experiments locally:

```bash
git clone https://github.com/rivas-vega/Advanced-learning-for-text-and-graph-data.git
cd Advanced-learning-for-text-and-graph-data

# Create virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install torch torchvision torchaudio
pip install transformers datasets accelerate peft
pip install torch-geometric
pip install jupyterlab
```

---

## 👤 Author

**Pedro** ([@rivas-vega](https://github.com/rivas-vega))  
*Master M2 MVA, ENS Paris-Saclay*  
*B.S. in Mathematics, Universidad de Sevilla*
