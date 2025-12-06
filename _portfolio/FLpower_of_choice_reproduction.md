---
title: "Federated Learning: Biased Client Selection Reproduction"
excerpt: "Developed a comprehensive tutorial for the Flautim Platform, focusing on the reproducibility of the paper \"Towards understanding biased client selection in federated learning\" [Jee Cho et. al, 2022]. <br/> <br/><img src='/images/power_of_choice_loss.png' alt='power of choice - loss' width='600'>"
collection: portfolio
---

Developed a comprehensive tutorial for the [Flautim Platform](https://flautim.futurelab.dcc.ufmg.br/), focusing on the reproducibility of the paper "Towards understanding biased client selection in federated learning" [Jee Cho et. al, 2022].

<img src='/images/power_of_choice_loss.png' alt='power od choice - loss' width='600'>

Code available at [https://github.com/carlabferreira/flautim_tutoriais/blob/main/TUTORIAL_4.ipynb](https://github.com/carlabferreira/flautim_tutoriais/blob/main/TUTORIAL_4.ipynb)

### Implementation
Utilized Python and the Flower Framework to architect a federated environment.

### Simulation
Modeled a network of 100 clients, implementing a probabilistic algorithm to select 3 clients per round (from 30 candidates) based on dataset size and local loss.

### Objective
To empirically demonstrate the impact of non-uniform client selection on global model convergence and bias.