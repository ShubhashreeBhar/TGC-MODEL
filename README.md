# 📈 Transaction Graph Contrastive (TGC) Model for Phishing Detection

This project implements a Transaction Graph Contrastive (TGC) framework for detecting phishing nodes in blockchain transaction networks.

The model leverages graph-based representation learning using DGL and PyTorch to learn high-quality node embeddings through a Graph Attention Network (GAT) encoder trained with contrastive learning (InfoNCE loss).

The learned embeddings are then used by an XGBoost classifier to improve phishing detection performance, particularly in imbalanced datasets.

## ➡️ Key features:

🔹Builds a directed transaction graph from raw CSV data

🔹Generates node-level features and ego-graphs

🔹Trains a GAT-based encoder using InfoNCE contrastive loss

🔹Extracts robust embeddings for nodes

🔹Classifies nodes as phishing/non-phishing using a boosted tree model

🔹Rich, color-coded console output with detailed metrics and confusion matrix

## ⚙️ Tech stack:
PyTorch · DGL · NetworkX · XGBoost · Scikit-learn · Rich · TQDM

## 🛡️ Purpose: 
Helps improve phishing detection accuracy in transaction networks by leveraging self-supervised graph learning.

## ✅ Status: 
Working prototype with tested Colab integration.
