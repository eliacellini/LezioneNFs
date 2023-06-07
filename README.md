# Normalizing Flows
## Corso di [Reti Neurali](https://www.fisicamagistrale.unito.it/do/corsi.pl/Show?_id=6e6f), 8/06/2023

## Referenze:
* **Teoria**:
  1. Inferenza variazionale: [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf), C. Bishop (capitolo 10).
  2. Primo Articolo: [Variational Inference with Normalizing Flows](https://arxiv.org/abs/1505.05770), D. J. Rezende e S. Mohamed
  3. Introduzione ai Normalizing Flows: [Normalizing Flows for Probabilistic Modeling and Inference](https://arxiv.org/abs/1912.02762), G. Papamakarios et al.
 
* Tutorial
  1. Tutorial lezione: <a target="_blank" href="https://colab.research.google.com/github/eliacellini/LezioneNFs/blob/eff7f88fc942119f4d8f86f4e748dac320dcd671/NFRetiNeurali.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
  2. Tutorial simile ma in [Keras](https://keras.io/examples/generative/real_nvp/)
  3. Ottimo tutorial sui normalizing flows per la computer vision: [Pytorch](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial11/NF_image_modeling.html), [JAX+FLAX](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/JAX/tutorial11/NF_image_modeling.html)
  
* **Architetture popolari**:
  1. [Density estimation using Real NVP](https://arxiv.org/abs/1605.08803), L. Dinh et al.
  2. [Glow: Generative Flow with Invertible 1x1 Convolutions](https://arxiv.org/abs/1807.03039),  D. Kingma e P. Dhariwal
  3. [FFJORD: Free-form Continuous Dynamics for Scalable Reversible Generative Models](https://arxiv.org/abs/1810.01367), W Grathwohl et al. (Continuous NFs)

## Normalizing Flows per campionare distribuzioni di Boltzmann
* **Fisica Chimica**:
  1. [Boltzmann generators: Sampling equilibrium states of many-body systems with deep learning](https://www.science.org/doi/10.1126/science.aaw1147), F. Noé et al.

* **Quantum Field Theory**:
  1. [Flow-based generative models for Markov chain Monte Carlo in lattice field theory](https://arxiv.org/abs/1904.12072), M. S. Albergo et al.,
  2. [Estimation of Thermodynamic Observables in Lattice Field Theories with Deep Generative Models](https://arxiv.org/abs/2007.07115), K. A. Nicoli et al.
  3. [Introduction to Normalizing Flows for Lattice Field Theory](https://arxiv.org/abs/2101.08176) M.S. Albergo et al.
 
 * **Cosa abbiamo fatto/facciamo**:
    1. [Stochastic normalizing flows as non-equilibrium transformations](https://arxiv.org/abs/2201.08862) M. Caselle et al.
    2. Simulazioni per teorie di stringa efficace (in preparazione), [Talk](https://www.youtube.com/watch?v=aiwCLeFqvg4)
    3. Stochastic normalizing flows per teorie di gauge su reticolo (progetto appena partito)


