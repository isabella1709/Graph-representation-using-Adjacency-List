# Graph Representation Using Adjacency List

This repository contains a Python-based implementation of a **directed, labeled, and weighted graph** using **adjacency lists**, demonstrated in a Jupyter Notebook. It is designed for educational and practical purposes, offering a clear and intuitive introduction to graph data structures in Python.

## 📘 Contents

- `Ajacency_List.ipynb`: The main notebook demonstrating how to represent and manipulate a graph using adjacency lists
- Example code for adding vertices and edges with labels and weights
- Simple, readable implementation for learning and experimentation

## 📌 Features

This project implements a **directed, labeled, and weighted graph** using an adjacency list representation. The following operations are supported:

### 🧱 Vertex Management
- `add_vertex`: Add a new vertex to the graph
- `remove_vertex`: Remove a vertex from the graph
- `vertex_exists`: Check if a vertex exists in the graph

### 🔁 Edge Operations
- `add_edge`: Add a directed and weighted edge between two vertices
- `remove_edge`: Remove an existing edge
- `edge_exists`: Check whether an edge exists between two vertices
- `get_weight`: Retrieve the weight of a specific edge

### 📈 Degree Computation
- `degree`: Get the total degree (in + out) of a vertex
- `out_degree`: Get the out-degree of a vertex
- `enter_degree`: Get the in-degree of a vertex

### 📋 Printing and Validation
- `print_adj_list`: Display the adjacency list
- `__str__`: Return a string representation of the graph
- `valid_weight`: Check if a weight is valid (e.g., non-negative)

These methods provide a flexible and educational environment for working with graph data structures.

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/isabella1709/Graph-representation-using-Adjacency-List.git
   cd Graph-representation-using-Adjacency-List
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook notebooks/Ajacency_List.ipynb
   ```

## 👩‍💻 Author

Developed by [Isabella Berkembrock](https://github.com/isabella1709)
