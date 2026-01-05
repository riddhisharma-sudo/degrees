# CS50 AI – Degrees of Separation

# Degrees of Separation – Actor Network Analysis 🎬

This project computes the **degrees of separation between two actors** using
**Breadth-First Search (BFS)** on a real-world movie dataset from IMDb.

It also includes an **interactive graph visualization** to visually explain
the shortest connection path between actors.

---

## 🚀 Features

- Finds the shortest actor-to-actor connection (Degrees of Separation)
- Uses **graph traversal (BFS)**
- Works on real IMDb datasets (CS50 AI)
- Interactive **network visualization** using PyVis
- Clean, modular Python code

---

## 🧠 How It Works

- **Nodes** → Actors  
- **Edges** → Movies connecting actors  
- **Algorithm** → Breadth-First Search (guarantees shortest path)

---

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install networkx pyvis
2. Run the CLI version
bash
Copy code
python degrees.py large
3. Run the visualization
bash
Copy code
python visualize.py "Emma Watson" "Jennifer Lawrence"
This generates graph.html, which you can open in your browser.
```bash
pip install networkx pyvis


Why We Used PyVis in This Project
Short answer:

PyVis lets us turn an abstract graph algorithm (BFS) into an interactive, explainable visual graph using Python only.
