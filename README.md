# pagerank-algorithm

A Python project implementing the PageRank algorithm to rank web pages and academic papers based on link structure using eigenvector and power iteration methods. This project demonstrates crawling, transition matrix construction, damping factor handling, and ranking analysis on datasets such as Harvard University’s website.

---

## Key Features

- Implements PageRank using both eigenvector and power iteration methods  
- Handles sink nodes using damping factor `p`  
- Analyzes the effects of adding or removing links on rankings  
- Applies to both web link networks and citation networks  
- Includes crawling and adjacency matrix construction from Harvard.edu  

---

## Project Structure

- `data.json` – Contains crawled link data  
- `MidRep_code.py` – Python script with crawler logic  
- `pagerank.ipynb` – Jupyter notebook implementing PageRank  
- `README.md` – Project overview and documentation  

---

## Technologies Used

- Python  
- NumPy  
- JSON  
- Custom web crawling logic  
- Jupyter Notebook  

---

## Core Concepts

- **Adjacency Matrix:** Represents link structure between nodes (pages or papers)  
- **Transition Matrix:** Combines link structure with random jump probabilities  
- **Damping Factor (p):** Ensures strong connectivity by handling random jumps  
- **Perron-Frobenius Theorem:** Guarantees a unique steady-state ranking  

---

## Applications

- Ranking academic papers by citations  
- Ranking web pages (e.g., Harvard University site)  
- Influence analysis in social, citation, and web networks  

---

## Author

**Sri Kalyan Reddy Akiti**  
Data Science and Artificial Intelligence  
