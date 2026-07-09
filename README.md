# SCT_SE_3 - Sudoku Solver

## SkillCraft Technology Internship

### Task 03 - Sudoku Solver

---

## 📌 Project Overview

This project was developed as part of the **SkillCraft Technology Software Engineering Internship**. The application automatically solves a standard 9×9 Sudoku puzzle using the **Backtracking Algorithm**. It accepts an incomplete Sudoku grid, validates each possible move according to Sudoku rules, and finds the correct solution efficiently.

---

## 🎯 Objectives

The main objectives of this project are:

- Develop a Python-based Sudoku solver.
- Accept an incomplete 9×9 Sudoku puzzle as input.
- Automatically solve the puzzle using a recursive algorithm.
- Ensure that every solution follows all Sudoku constraints.
- Display both the original and solved Sudoku grids.
- Improve understanding of recursion and backtracking techniques.

---

## ⚙️ Algorithm Used

### Backtracking Algorithm

The Sudoku solver uses the **Backtracking Algorithm**, a recursive depth-first search technique widely used for solving constraint satisfaction problems.

### Working Procedure

1. Search for the first empty cell in the Sudoku grid.
2. Try placing numbers from **1 to 9** in that cell.
3. Check whether the number is valid by verifying:
   - The number does not already exist in the same row.
   - The number does not already exist in the same column.
   - The number does not already exist in the corresponding 3×3 subgrid.
4. If the number is valid, place it in the cell.
5. Recursively solve the remaining puzzle.
6. If no valid number can be placed later, remove the previous number (backtrack) and try the next possible value.
7. Continue until the entire puzzle is solved.

### Advantages

- Guarantees a correct solution if one exists.
- Simple and efficient for standard Sudoku puzzles.
- Demonstrates recursive problem-solving techniques.
- Widely used in AI and constraint satisfaction problems.

---

## ✨ Features

- Solves standard 9×9 Sudoku puzzles.
- Uses the Backtracking Algorithm.
- Displays the original Sudoku puzzle.
- Displays the solved Sudoku puzzle.
- Validates every move before placing a number.
- Uses recursion for efficient searching.
- Clean and beginner-friendly Python implementation.

---

## 🛠️ Technologies Used

- Python 3
- Backtracking Algorithm
- Recursion

---

## 📂 Project Structure

```
SCT_SE_3/
│
├── sudoku_solver.py
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── screenshots/
```

---

## 🚀 Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Program

```bash
python sudoku_solver.py
```

---

## 📊 Sample Output

```
Original Sudoku

5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
...

Solved Sudoku

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
...
```

---

## 📚 Learning Outcomes

Through this project, I gained practical knowledge of:

- Python programming fundamentals
- Recursive function implementation
- Backtracking algorithm
- Constraint satisfaction problems
- Two-dimensional array manipulation
- Algorithmic problem solving
- Logical thinking and debugging

---

## 🔮 Future Enhancements

- Develop a graphical user interface (GUI) using Tkinter.
- Allow users to enter custom Sudoku puzzles.
- Read Sudoku puzzles from text or CSV files.
- Add a puzzle generator with different difficulty levels.
- Visualize the solving process step by step.

---

## 👩‍💻 Author

**Name:** Susmija

**Internship:** SkillCraft Technology

**Repository:** SCT_SE_3
