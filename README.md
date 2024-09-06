
# Transaction Monitoring with GraphSAGE and NVFlare

This repository contains Jupyter notebooks for interacting with a pre-trained Graph Neural Network (GNN) model based on GraphSAGE. The model, trained on the **Elliptic++ dataset**, is designed to classify Bitcoin transactions as either licit or illicit in a federated learning setup using **NVFlare**.

## Contents

- **notebooks/**
  - `model_interaction.ipynb`: Interacts with a pre-trained GraphSAGE model to classify transactions and visualize their embeddings.
  - `model_inference.ipynb`: Provides steps to preprocess transaction data from the Elliptic++ dataset for model interaction.
  - `model_visualization.ipynb`: Visualizes transaction embeddings using PCA and highlights the distinction between normal and fraudulent transactions.

## Requirements

Make sure to install the required libraries before running the notebooks:

```bash
pip install torch torch-geometric matplotlib scikit-learn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gnn-transaction-monitoring.git
   cd gnn-transaction-monitoring
   ```

2. Open any notebook to interact with the pre-trained GNN model.

3. Visualize transaction embeddings and classify transactions by running the provided notebooks in a Jupyter environment.


