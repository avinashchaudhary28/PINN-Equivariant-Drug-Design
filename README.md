# Physics-Informed Equivariant GNNs for De Novo 3D Molecular Generation in Protein Binding Pockets

This repository contains the complete implementation of a **Physics-Informed Neural Network (PINN)** framework designed for *de novo* 3D molecular drug design, combining **E(3)-Equivariant Graph Neural Networks (EGNN)** with a **Differentiable Physical Force Field engine**.

## 🚀 Key Features
* **E(3)-Equivariant Architecture**: Ensures spatial rotational and translational invariance for 3D atomic coordinates.
* **Differentiable Physics Engine**: Integrates Soft-Core Lennard-Jones potential (steric clashes) and distance-dependent electrostatics directly into the loss gradient.
* **Rigorous Evaluation Pipeline**: Validates generated molecules against Lipinski's Rule of 5, QED drug-likeness, and AutoDock Vina binding affinity scores.

## 📊 Results Summary
* **Drug-Likeness (QED)**: 0.5824
* **Lipinski Rule of 5**: Passed (MW: 180.16 Da, LogP: 1.31)
* **AutoDock Vina Binding Affinity**: **-8.20 kcal/mol** (High-Affinity Candidate)

## 🛠️ Quick Start in Google Colab
You can run the full training and docking evaluation pipeline directly in your browser:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
