# 🧠 Day 29 — Capstone Implementation (AI Maze Solver using A*)

### 🎯 Objective  
Implement the **A\*** (A-star) search algorithm to solve a 2D maze, visualize the solution path, benchmark its speed, and store results for deployment/portfolio use.

---

## 🧩 What Was Built Today  
- Generated a **20 × 20 synthetic maze grid**
- Added **random walls**
- Implemented **A\*** using:
  - **Priority Queue (Min-Heap)**
  - **Manhattan Distance heuristic**
  - **Optimal path backtracking**
- Benchmarked model execution time
- Visualized:
  - Path taken
  - Start `⭕` and target `❌`
- Saved benchmark results + stats into:

---

## 🧠 Key Learnings  
| Concept | Takeaway |
|--------|---------|
| A* Search | Finds optimal path using cost + heuristic |
| Manhattan Distance | Best for grid-based movement |
| Priority Queue | Optimizes node selection |
| Data Leakage Prevention | Only preprocessing before training |
| Benchmarking | Essential before deployment |
| Logs | Helps track model performance over time |

---

## ⚙️ Evaluation Insights  
✅ **Path Found Successfully**  
⏱️ **Execution time recorded and saved for future dashboard use**
