# Graph-Based Toxic Community Detection and Toxicity Propagation Analysis on Reddit Networks

## Project Overview

This project focuses on analyzing toxic behavior, community polarization, and toxicity propagation in online social networks using the Reddit Hyperlink Network Dataset from the Stanford Network Analysis Project (SNAP).

The project aims to study how toxic interactions spread between online communities, identify influential toxic communities, detect polarized groups, and evaluate how network interventions can reduce toxicity propagation.

The project combines multiple concepts from Social Network Analysis and Data Science, including:

* Graph Analysis
* Community Detection
* Network Robustness Testing
* Information Spread Simulation
* Toxicity and Sentiment Analysis

The project also simulates real-world problems faced by modern social media platforms such as:

* toxic discussions,
* online harassment,
* hate communities,
* misinformation spread,
* and online polarization.

---

# Dataset

## Dataset Name

Reddit Hyperlink Network Dataset

## Dataset Source

Stanford Network Analysis Project (SNAP)

## Dataset Description

The dataset represents interactions between Reddit communities (subreddits).

* Each node represents a subreddit.
* Each directed edge represents a hyperlink or reference from one subreddit to another.

The dataset includes:

* source subreddit,
* target subreddit,
* timestamps,
* sentiment labels,
* and text-related properties.

The project uses the Reddit Hyperlinks Body dataset because it provides richer textual information and stronger interaction signals.

---

# Project Objectives

## 1. Exploratory Network Analysis

* Build and visualize the network graph.
* Analyze:

  * number of nodes and edges,
  * degree distribution,
  * network density,
  * clustering patterns,
  * connectivity.

## 2. Toxicity and Sentiment Analysis

* Analyze interaction sentiment and toxicity behavior.
* Detect toxic communities and negative interactions.
* Identify influential toxicity hubs.

## 3. Community Detection

* Detect subreddit communities using:

  * Louvain Algorithm,
  * Girvan-Newman Algorithm.
* Measure modularity and community structure quality.

## 4. Network Robustness Testing

* Simulate:

  * random failures,
  * targeted attacks,
  * toxic hub removal.
* Analyze network fragmentation and resilience.

## 5. Information Spread Simulation

* Simulate toxicity propagation using:

  * SIS Model,
  * Independent Cascade Model.
* Analyze spread speed and affected communities.

---

# Technologies and Libraries

## Python Libraries

* pandas
* numpy
* networkx
* matplotlib
* pyvis
* scikit-learn

## NLP Libraries

* nltk
* textblob
* VADER Sentiment Analyzer

---

# Project Structure

```text
reddit-toxic-network-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_preprocessing.ipynb
│   ├── 02_network_analysis.ipynb
│   ├── 03_toxicity_analysis.ipynb
│   ├── 04_community_detection.ipynb
│   ├── 05_robustness_testing.ipynb
│   └── 06_spread_simulation.ipynb
│
├── outputs/
│   ├── figures/
│   ├── graphs/
│   └── animations/
│
├── docs/
│   ├── report/
│   └── presentation/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Workflow

The project workflow is organized into the following phases:

1. Dataset Loading and Preprocessing
2. Graph Construction
3. Exploratory Network Analysis
4. Toxicity and Sentiment Analysis
5. Community Detection
6. Network Robustness Testing
7. Information Spread Simulation
8. Visualization and Final Reporting

---

# Team Responsibilities

| Member   | Responsibility                          |
| -------- | --------------------------------------- |
| Member 1 | Graph Construction and Network Analysis |
| Member 2 | Toxicity and Sentiment Analysis         |
| Member 3 | Community Detection                     |
| Member 4 | Robustness Testing                      |
| Member 5 | Spread Simulation and Final Integration |

---

# Expected Results

The project aims to answer questions such as:

* Which communities are the most toxic?
* Which communities act as bridges between groups?
* How does toxic behavior spread across communities?
* How robust is the network against attacks?
* Does removing toxic hubs reduce toxicity propagation?

---

# How to Run

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Open Jupyter Notebook

```bash
jupyter notebook
```

---

# Expected Deliverables

* Cleaned and processed dataset
* Graph analysis notebooks
* Community detection results
* Toxicity analysis results
* Spread simulation visualizations
* Final report
* Final presentation

---

# Real-World Relevance

This project demonstrates how graph analysis and machine learning techniques can help analyze and reduce harmful behavior in online social platforms.

The results can contribute to:

* moderation systems,
* toxicity monitoring tools,
* safer recommendation systems,
* and healthier online communities.
