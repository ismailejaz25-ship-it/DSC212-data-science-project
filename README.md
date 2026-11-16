# Recursive Spectral Modularity Partitioning on Karate Club Graph

## Project Overview

This project explores community detection and graph analysis using Zachary's Karate Club Network. It implements recursive spectral modularity partitioning to identify communities and studies how the network structure and node centrality measures evolve during partitioning.

The project also explores additional graph-based machine learning and network science techniques.

## Objectives

- Implement spectral modularity-based community detection.
- Perform recursive partitioning of network communities.
- Visualize community structures at different partition stages.
- Analyze degree, betweenness and closeness centrality, and clustering coefficients.
- Explore semi-supervised node classification using Graph Convolutional Networks (GCN).
- Compare community detection methods.
- Apply link prediction algorithms.
- Visualize graph nodes using spectral embeddings.

## Methods and Algorithms

1. **Spectral Modularity Partitioning:** Uses the modularity matrix and its leading eigenvector to divide communities.
2. **Recursive Community Detection:** Repeatedly partitions the largest community.
3. **Network Centrality Analysis:** Studies degree, betweenness, closeness and clustering coefficients.
4. **Graph Convolutional Network:** Explores semi-supervised node classification using PyTorch Geometric.
5. **Girvan–Newman and Louvain:** Compares alternative community detection algorithms.
6. **Link Prediction:** Uses Jaccard similarity and Adamic–Adar indices.
7. **Spectral Embedding:** Projects graph nodes into a two-dimensional space.

## Dataset

The project uses the Zachary's Karate Club graph, a classic social network dataset available directly through NetworkX.

- 34 nodes
- 78 edges
- Represents friendships among members of a university karate club.

## Technologies Used

- Python
- NumPy
- Pandas
- NetworkX
- Matplotlib
- Scikit-learn
- PyTorch
- PyTorch Geometric

## Repository Structure

```text
DSC212-Data-Science-Project/
│
├── DSC212_Project.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Execute the cells sequentially.

## Learning Outcomes

This project provides practical exposure to:

- Graph theory and network
