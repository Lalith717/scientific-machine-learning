# Scientific Machine Learning

This repository contains two projects completed as part of my exploration of scientific machine learning:

1. **Physics-Informed Neural Networks (PINNs)** for solving partial differential equations and studying optimization behavior.
2. **Fourier Neural Operators (FNOs)** for learning dynamical systems from spatiotemporal data.

## Physics-Informed Neural Networks

In this project, I implemented PINNs to solve benchmark PDEs and investigated some of the challenges associated with training physics-informed models. The study focused on understanding how PINNs learn different spatial frequencies and how their optimization behavior differs from conventional supervised learning approaches.

Key outcomes:

* Implemented PINN-based PDE solvers using PyTorch.
* Compared PINN and data-driven training across spatial frequencies.
* Analyzed spectral bias and optimization characteristics of PINNs.

## Fourier Neural Operators

This project explored neural operator learning using Fourier Neural Operators. The models were trained on spatiotemporal trajectory data and evaluated for their ability to generalize across different operating conditions and resolutions.

Key outcomes:

* Implemented Fourier Neural Operators for learning dynamical systems.
* Evaluated model performance across multiple spatial resolutions.
* Fine-tuned pretrained FNOs under distribution shift, reducing prediction error by 48% compared to training from scratch.

## Tools

* Python
* PyTorch
* NumPy
* Matplotlib
* Jupyter Notebook

## Repository Contents

```text
PINNs.ipynb    # PINN implementation and experiments
FNO.ipynb      # FNO implementation and experiments
```
