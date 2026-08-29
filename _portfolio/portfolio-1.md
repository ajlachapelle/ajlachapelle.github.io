---
title: "Graph Neural Network"
excerpt: "A deep learning AI made for current recognition in chip circuits<br/><img src=''>"
collection: portfolio
---

Overview
======
Neural networks are a type of algorithm that adjusts (or "trains") a large array of simple functions to approximate complex computational tasks. A graph neural network is a subtype that applies mathematical graph theory to leverage neural networks for more abstract problems. In this project, we represent a circuit as a graph of nodes and connecting wires, which allows the network to learn how electrical current flows in the circuit without doing complex physics calculations.

The technical aspects of the circuit (i.e. which components were used and their physical quantities like resistance) were provided by a classmate:
<img
  class="fit-picture"
  src="https://ajlachapelle.github.io/files/schematic.jpg"
  alt="Original" />

 My job was to create a neural graph that matched the description, and implement the learning algorithm.

This project is my most recent, and my first deep learning algorithm that I programmed and trained from scratch. It also gave me experience with collaboration and writing a program to match technical specifications.

[Source Code](https://github.com/ajlachapelle/CurrentPrediction)
======
Written in Python, using PyTorch and Weights & Biases

Future Work
======
The initial version of this project is complete, but I plan to add to it by creating an automatic graph converter using a more standard method in physics (specifically, modelling the circuit as wire nodes connected by resistors).
