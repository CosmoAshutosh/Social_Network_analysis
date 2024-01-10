# Social Network Analysis

This repository contains a Python script for performing Social Network Analysis (SNA) on real-world datasets. The script utilizes the NetworkX library to create, analyze, and visualize networks. Three different datasets, representing a Congress network, a Facebook friendship network, and an email communication network, are used for the analysis.

## Prerequisites

- Python 3
- Jupyter Notebook (for running the provided `.ipynb` file)
- Required Python libraries: pandas, matplotlib, networkx

## Dataset

The script loads three datasets:
# Dataset is take from: https://snap.stanford.edu/data/

1. Congress network: Representing relationships between members of Congress.
2. Facebook friendship network: Representing friendships between Facebook users.
3. Email communication network: Representing the communication between individuals in a university email system.

## Analysis and Visualization

The script performs the following analyses on each dataset:

1. **Graph Creation:** The script creates graphs from the datasets using NetworkX, representing the relationships between entities.

2. **Average Degree Calculation:** Calculates the average degree of the real-world graph and creates corresponding synthetic graphs (G(n,p) and Watts-Strogatz) with the same average degree.

3. **Degree Centrality Distribution:** Plots histograms of degree centrality distribution for the real-world and synthetic graphs.

4. **Betweenness Centrality Distribution:** Plots histograms of betweenness centrality distribution for the real-world and synthetic graphs.

5. **Closeness Centrality Distribution:** Plots histograms of closeness centrality distribution for the real-world and synthetic graphs.

6. **Clustering Coefficient Distribution:** Plots histograms of clustering coefficient distribution for the real-world and synthetic graphs.

7. **Average Shortest Path Lengths:** Calculates and compares the average shortest path lengths for the largest connected components of the real-world and synthetic graphs.

## Running the Code

1. Open the provided Jupyter Notebook file (`Assignment-1.ipynb`) in a Jupyter environment.
2. Make sure the required libraries are installed (`pandas`, `matplotlib`, `networkx`).
3. Execute the cells in the notebook sequentially.

## Results

The script generates various visualizations and summary statistics, providing insights into the structure and centrality of the social networks in the given datasets.

## Author

[ASHUTOSH MISHRA]

## Acknowledgments

- This work is part of [Your Course or Project Name].
- The datasets used in this analysis are sourced from [Dataset Sources].
- Special thanks to the creators of the NetworkX library.
