---
title: Neuro Fuzzy Logic Midterm Notes
categories: [Notes]
tags: L

---

---
* Supervised Learning algorithms require a target output
  * As opposed to unsupervised in which has no target output
  * Reinforcement is gives feedback
* Underfitting can be a result of having a lack of hidden neurons or lack of data
* Overtraining can be a result of too many hidden neurons 
* Each neuron has many inputs but only one output
* Activation layer of hidden layer must be nonlinear
  * Other layers (I/O) can be linear

## Shunting Model

* X* = -Ax + (B-x)S+ -(D+X)S-
* S+ = Excitatory Input to neuron 
* S- = Inhabitory Input to neuron 
* A = Passive Decay Rate 
* B = Upper Bound of neural activity 
* D = Lower Bound of neural activity

