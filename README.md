# Applied Stochastic Processes in Machine Learning

This repository showcases a collection of projects focused on applying the principles of **Stochastic Processes** (Probability Theory, Markov Chains, Random Walks, Queueing Theory) to model, analyze, and optimize various Machine Learning and data science problems.

The work here emphasizes moving beyond standard ML library usage to tackle fundamental challenges in system design, data dimensionality, and algorithmic performance using rigorous mathematical modeling.

## Core Applications & Techniques

The projects in this repository demonstrate expertise across the following domains:

### 1. System Modeling and Optimization (Queueing Theory)
We use stochastic models to analyze the performance and stability of computational systems. This is particularly relevant for understanding latency, throughput, and resource allocation in live-serving ML models, data pipelines, and cloud computing architectures.

### 2. Dimensionality Reduction and Data Analysis (Random Walks & PCA)
We apply stochastic principles to classic data science problems, using concepts like random walks and spectral graph theory to understand data distribution, clustering, and noise reduction.

### 3. Time Series and Sequential Data (Markov Chains)
Projects explore the use of Markov models and related processes to analyze sequential data, predict transitions, and build generative models where the future state depends solely on the current state.


## Project List

The following projects are included in this repository, illustrating different applications of stochastic processes:

### A. M/M/1 Queue Theory for System Latency Modeling
This project models a basic Machine Learning service endpoint (e.g., a simple prediction API) as an M/M/1 queue.
* **Goal:** To calculate key performance indicators like **average waiting time ($\boldsymbol{W_q}$)**, **average queue length ($\boldsymbol{L_q}$)**, and **system utilization ($\boldsymbol{\rho}$)**.
* **Methodology:** Implementation of the birth-death process and steady-state equations to analyze system stability and predict latency under various traffic loads (arrival rates $\lambda$ and service rates $\mu$).
* **Relevance:** Critical for optimizing resource allocation in production environments and setting service-level agreements (SLAs).

### B. Mars Rover Sample Classification using PCA
This project analyzes a dataset of spectral data gathered by a simulated Mars Rover.
* **Goal:** To accurately classify rock and soil samples despite high dimensionality and noise.
* **Methodology:** **Principal Component Analysis (PCA)** is utilized for dimensionality reduction. The project explores the connection between PCA and **Random Matrix Theory** (a sub-field of stochastic processes) to estimate the true rank and optimal number of components for feature extraction.
* **Relevance:** Demonstrates robust feature engineering and noise reduction for classification tasks in highly dimensional data.


## Technologies Used

* **Programming:** Python (Primary)
* **Libraries:** NumPy, Pandas, Scipy (for statistical distributions and solving differential equations), Matplotlib (for visualization), Scikit-learn (for classification baseline).
* **Modeling:** Implementation of custom functions for stochastic processes (e.g., Markov Chain simulation, queueing formulas) without relying on high-level ML frameworks.


