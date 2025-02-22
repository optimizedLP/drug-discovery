## Predicting Protein-Ligand Binding Affinity Using GNNs

- This project focuses on predicting protein-ligand binding affinity using Graph Neural Networks (GNNs). 
- It demonstrates how to generate synthetic ligand molecules, represent them as graphs, and train a GNN model to predict binding affinity. 


### Project Overview

What is Protein-Ligand Binding Affinity?
* Protein-ligand binding affinity measures how strongly a small molecule (ligand) binds to a protein target. It is a key metric in drug discovery, as high-affinity binding is often required for a drug to be effective.

What Does This Project Do?

1. Synthetic Data Generation:
Generates synthetic ligand molecules using RDKit.
Simulates protein-ligand binding affinities.

2. Molecular Representation:
Represents molecules as graphs (nodes = atoms, edges = bonds).
Extracts molecular features using RDKit.

3. Graph Neural Network (GNN) Model:
Builds and trains a GNN model using PyTorch Geometric.
Predicts binding affinity based on molecular graphs.

4. Evaluation:
Evaluates the model using Mean Squared Error (MSE).
Visualizes predicted vs. true binding affinities.

5. Additional Features:
Visualizes molecular graphs.
Analyzes feature importance.
Tunes hyperparameters for better performance.


### Results
Model Performance
Mean Squared Error (MSE): 0.0844

Interpretation: The model's predictions are, on average, ~0.29 units away from the true binding affinity values.

### Future Work
1. Improve Synthetic Data
2. Experiment with GNN Architectures:
3. Hyperparameter Optimization:
4. Deploy the Model:


1. Improve Synthetic Data
2. Experiment with GNN Architectures
3. Hyperparameter Optimization
4. Deploy the Model

### Acknowledgements
* RDKit: For molecular representation and visualization.
* PyTorch Geometric: For GNN implementation.