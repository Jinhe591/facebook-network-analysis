📘 Facebook Network Analysis — Ego Network Study
📌 Project Overview

This project analyzes the Facebook social network dataset provided by the Stanford Network Analysis Project (SNAP).
The goal is to model the dataset as a graph and perform fundamental network analysis operations using Python and NetworkX.

The notebook constructs a social graph where:

    Nodes 👥 represent Facebook users

    Edges 🔗 represent friendships between users

The analysis focuses on graph structure, node connectivity, and ego network extraction.
🎯 Objectives

The main objectives of this project are:

    🔨 Construct a social network graph from raw edge data

    📊 Compute the degree of each node

    📐 Generate the adjacency matrix

    🕸️ Extract ego networks for all users

    🔍 Implement an interface to search nodes and retrieve their degree

    📈 Perform basic network statistics analysis

Example requirement:
   Node 915 → Degree 35


📂 Dataset

Dataset used:
ego-Facebook

Source:
Stanford SNAP Repository

Dataset Description:

    🔄 Undirected social network

    🤝 Facebook friendship relationships

    🧩 Combined ego networks

    🔒 No personal or private user information

🧱 Project Structure
text

facebook-network-analysis/
│
├── 📁 data/
│   └── facebook_combined.txt
│
├── 📁 notebooks/
│   └── facebook_analysis.ipynb
│
├── 📁 results/
│   └── node_degrees.csv
│
├── 📦 requirements.txt
└── 📘 README.md

⚙️ Technologies Used

    🐍 Python 3

    🔗 NetworkX

    🐼 Pandas

    🔢 NumPy

    📊 Matplotlib

    📓 Jupyter Notebook

🔬 Methodology
1. Graph Construction

The dataset edge list is loaded and converted into a graph using NetworkX.
2. Degree Analysis

The degree of each node is computed to measure connectivity.
3. Adjacency Matrix

The full adjacency matrix of the network is generated to represent connections mathematically.
4. Ego Networks

For every node, an ego network is created consisting of:

    🎯 The node itself (ego)

    👥 Its immediate neighbors

    🔗 Connections among those neighbors

5. Node Search Interface

A simple interface allows users to input a node ID and retrieve its degree.
📊 Network Properties

The notebook computes:

    📍 Number of nodes

    🔗 Number of edges

    📉 Graph density

    📊 Average degree

    🕸️ Ego network statistics

▶️ How to Run
1️⃣ Clone Repository
bash

git clone <https://github.com/Jinhe591/facebook-network-analysis>
cd facebook-network-analysis

2️⃣ Install Requirements
bash

pip install -r requirements.txt

3️⃣ Launch Notebook
bash

jupyter notebook

Open:
notebooks/facebook_analysis.ipynb

Run: all cells sequentially.
📈 Example Output
text

Node 915 → Degree 35

📁 Adjacency matrix and degree results are also exported as CSV files.
📚 Concepts Covered

    📐 Graph Theory

    🌐 Social Network Analysis

    ⭐ Degree Centrality

    🕸️ Ego Networks

    📊 Adjacency Matrices

    🧮 Network Modeling

✅ Submission Contents

    📓 Jupyter Notebook implementation

    📊 Processed results

    📂 GitHub repository

    📘 Documentation (README)

👤 Author

Hadi Assi
    🎓 Data Science Student

📜 License
     This project is for academic and educational purposes only.