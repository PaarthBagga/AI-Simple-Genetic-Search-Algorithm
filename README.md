# 🧬 AI - Simple Genetic Algorithm Project

## 📌 Project Overview
I developed this project with 10 group members for one of my courses. 

It implements a Simple Genetic Algorithm (SGA) to mimic evolutionary processes like natural selection, crossover, mutation, and elitism to solve optimization problems using different objective functions. The implementation includes three benchmark functions and two custom functions provided by our professor.

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** NumPy, Matplotlib, Tkinter
- **Technologies:** Git

---

## 🧠 Features:
- **Customizable Parameters:** Adjust population size, mutation rate, and generations.
- **Objective Function Selection:** Includes Sphere, Rosenbrock, and Himmelblau functions + custom functions.
- **Visualization:** Plots the convergence of the algorithm using Matplotlib.
- **Graphical User Interface (GUI):** Built using Tkinter for ease of use.

---

## 📊 Objective Functions
### 🔢 Sphere Function
- A simple unimodal function:


### 🔄 Rosenbrock Function
- A non-convex function:

### 🔀 Himmelblau Function
- A multimodal function with multiple local minima:

### 🔧 Custom Functions
- The algorithm also supports **user-defined** functions.

## 🖥️ Graphical User Interface (GUI)
The **Tkinter-based GUI** allows:
- Selection of ojective functions.
- Input for **variables, bounds, population size, generations, and mutation rate**.
- Running the algorithm and **visualizing results** in real-time.


---

## 📦 Installation and Execution

### 📌 Prerequisites
Ensure you have:
- **Python 3.8+**
- **pip** installed.

### 🔧 Installation
Run the following command to instal required dependencies:
```bash
pip install numpy matplotlib
```
(Tkinter comes pre-installed with Python.)

### ▶️ Running the Program
1. Clone the repository:
```
git clone https://github.com/PaarthBagga/AI-Simple-Genetic-Search-Algorithm.git
cd AI-Simple-Genetic-Search-Algorithm
```
2. Run the Genetic Algorithm GUI:
```
python genetic_algorithm.py
```

## 📈 Results & Visualizations

The best fitness score per generation is visualized using Matplotlib, a graph will be outputted as well as a message box that presents the best fitness score.


