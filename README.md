# 📡Game-Based Cellular Frequency Reuse Visualizer

## 🧩 Overview

This project is an interactive Python-based GUI application that visualizes the Cellular Frequency Reuse concept using a hexagonal grid model. It allows users to understand cluster size calculation and identify co-channel cells through an interactive game-based approach.

---

## 🎯Aim

To understand the cellular frequency reuse principle and determine the co-channel cells for a selected reference cell using an interactive visualization tool.

---

## 📖Theory

In cellular communication systems, frequency reuse is used to improve spectrum efficiency by reusing the same frequency in non-adjacent cells.

The cluster size (N) is calculated using:

N = i^2 + ij + j^2

Where:
- i = Shift in one direction
- j = Shift in 60° direction
- N = Cluster size

The reuse distance (D) between co-channel cells is calculated as:

D = R * sqrt(3N)

Where:
- R = Radius of the cell
- D = Distance between centers of co-channel cells

---

## 🛠 Technologies Used

- Python
- Tkinter (GUI)
- Math Library
- Object-Oriented Programming (OOP)

---

## 🎮Features

- Interactive hexagonal grid visualization
- User selection of reference cell
- Automatic calculation of cluster size
- Identification of valid co-channel cells
- Real-time validation:
  - Correct selection → Green
  - Incorrect selection → Red
- Visualization of reuse distance using connecting lines
- Restart functionality using Shift + R

---

## ⚙️ Working Procedure

1. Run the Python program.
2. Enter values of i and j.
3. The program calculates cluster size N.
4. GUI opens displaying a hexagonal grid.
5. Select a reference cell.
6. Identify and select co-channel cells.
7. The application validates selections.
8. Lines are drawn to show the reuse distance pattern.

---

## 📊 Example Input

Enter i: 1  
Enter j: 1  

Output:
N is 3

---

## 📚Learning Outcomes

- Understanding cellular network design
- Frequency reuse principle
- Cluster size calculation
- Co-channel interference concept
- Visualization of reuse distance
- Practical implementation of telecom theory concepts

---

## 🔁 Restart Option

Press Shift + R to reset the grid and start again.
