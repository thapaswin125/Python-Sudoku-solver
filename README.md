# 🔢 Python Sudoku Solver

This is a simple **Sudoku puzzle solver** built in Python using the **Backtracking Algorithm**. It takes an unsolved 9x9 Sudoku grid and fills in the correct numbers based on Sudoku rules.

---

## 🧠 How It Works

The program uses a **recursive backtracking** approach to try out possible number combinations and backtracks when a conflict is found. It ensures that:
- Each row has numbers 1–9 with no repetition
- Each column has numbers 1–9 with no repetition
- Each 3×3 grid has numbers 1–9 with no repetition

---

## 💻 Tech Stack

| Component   | Technology |
|-------------|------------|
| Language    | Python     |
| Algorithm   | Backtracking |
| UI (Optional) | Text-based |

---

## 📁 Project Structure

```
Python-Sudoku-solver/
│
├── sudoku_solver.py       # Main solving script
├── sample_board.txt       # Sample input Sudoku board (optional)
├── README.md              # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/thapaswin125/Python-Sudoku-solver.git
cd Python-Sudoku-solver
```

### 2. Run the Solver
Edit the Sudoku board inside the script or load from a file.

```bash
python sudoku_solver.py
```

### 3. Output
The solution (if exists) is printed in the console in a grid format.

---

## ✅ Example Input

```
board = [
  [5, 3, 0, 0, 7, 0, 0, 0, 0],
  [6, 0, 0, 1, 9, 5, 0, 0, 0],
  [0, 9, 8, 0, 0, 0, 0, 6, 0],
  ...
]
```

---

## ✍️ Author

**Thapaswin Reddy Kalikireddy**  
📧 [ktr@umd.edu](mailto:ktr@umd.edu)

---
