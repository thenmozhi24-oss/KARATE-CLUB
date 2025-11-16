# Karate Club Community Detection

This project performs community detection on the famous Zachary’s Karate Club network using **spectral modularity maximization**.  
The algorithm recursively splits the graph using the **leading eigenvector of the modularity matrix**, ensuring each split increases modularity.  
At every stage, the full graph is visualized with colored communities, and node-level metrics such as **degree, betweenness, closeness, and clustering** are computed.  
The project demonstrates how network structure analysis reveals the historical division of the club.

---

## 🔧 Features
- Spectral community detection (based on Newman’s modularity method)  
- Auto-handling of trivial or non-beneficial splits  
- Graph visualizations after each split  
- Centrality metric tracking across split steps  
- Final modularity evaluation

---

## 📊 Centrality Metrics Tracked
- Degree Centrality  
- Betweenness Centrality  
- Closeness Centrality  
- Clustering Coefficient  

Each is plotted across:  
**Split 0 → Split 1 → Split 2**

---

## 📁 How to Run
```bash
pip install networkx matplotlib numpy
python main.py   # or your file name

