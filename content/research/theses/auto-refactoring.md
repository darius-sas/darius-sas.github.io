---
title: "Automatic refactoring using Reinforcement Learning"
date: 2023-11-12T15:35:09Z
draft: false
---
by Darius Sas, Arcan SRL | [darius.sas@arcan.tech](mailto:darius.sas@arcan.tech)

# Introduction
Arcan performs static analysis on source code to pinpoint architectural smells, which are indicative of underlying technical debt and deviations from sound software design principles. Effectively managing technical debt involves not only detection but also the crucial step of repayment, achieved through the refactoring of architectural smells. 

The primary objective of this master's thesis is to explore a machine learning approach capable of providing the requisite refactoring steps for eliminating an architectural smell.

# Details
In Arcan, architectural smells, along with system components like classes and packages, are stored in a graph data structure. The process of eliminating an architectural smell involves identifying a sequence of steps, represented as a list of edges.

**Tasks:**
1. Develop a model for synthetically generating refactoring steps. This entails defining a model that identifies **possible** steps (but not necessarily the optimal ones) to eliminate the smell.
2. Implement the model to generate synthetic data.
3. Train a reinforcement learning model that discerns the optimal series of steps needed for resolving the architectural smell.
4. Evaluate the effectiveness of refactoring solutions based on the complexity to implement the solution within the code.