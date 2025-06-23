# pagerank-algorithm
A Python project implementing the PageRank algorithm to rank web pages and academic papers based on link structure using eigenvector and power iteration methods.

# pagerank-algorithm

A PageRank-based project implemented in Python to rank web pages and academic papers by importance using link structures and the damping factor concept. This project demonstrates both eigenvector and power iteration methods for score computation and includes crawling, transition matrix building, and analysis on real-world data like Harvard University’s website.

## 🧠 Key Features
- Implements PageRank using eigenvector & power iteration methods
- Handles sink nodes using damping factor `p`
- Analyzes effects of added links on rankings
- Applies to web links and citation networks
- Includes crawling and building adjacency matrix from Harvard.edu

## 📁 Project Structure
- `data.json` – Contains crawled link data
- `MidRep_code.py` – Python script with crawler logic
- `pagerank.ipynb` – Jupyter notebook implementing PageRank
- `README.md` – Project overview and documentation

## ⚙️ Technologies Used
- Python
- NumPy
- JSON
- Web crawling (custom logic)
- Jupyter Notebook

## 📊 Core Concepts
- **Adjacency Matrix:** Represents link structure between nodes (pages or papers)
- **Transition Matrix:** Combines link structure and random jump probabilities
- **Damping Factor (p):** Handles random jumps to ensure strong connectivity
- **Perron-Frobenius Theorem:** Guarantees a unique steady-state ranking

## 💡 Applications
- Ranking academic papers by citations
- Ranking web pages (e.g., Harvard University site)
- Influence analysis in social/citation/web networks

## 👨‍💻 Authors
**Sri Kalyan Reddy Akiti**  
data science and artificial intellignce 

