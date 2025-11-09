<p align="center">
  <img src="opticore_logo.png" alt="OptiCore Logo" width="150"/>
</p>

<h1 align="center" style="color:#D3D3D3; font-weight:normal;">
  Intelligent CPU Scheduling Optimizer
</h1>

<p align="center">
  <i>Optimizing CPU scheduling through intelligent algorithms.</i>
</p>

---

## Overview

**OptiCore** is an interactive tool that optimizes CPU scheduling using a Genetic Algorithm (GA).  
It benchmarks traditional scheduling algorithms like FCFS, SJF, Priority, and Round Robin, and then evolves optimized hybrids that minimize average waiting time, turnaround time, and context switching.

---

## Features

- Compare multiple baseline scheduling algorithms (FCFS, SJF, Priority, Round Robin).  
- Optimize scheduling dynamically with a Genetic Algorithm.  
- Visualize results with Gantt charts and performance graphs.  
- Interactive interface for setting process parameters and GA configurations.  
- Reports key performance metrics:
  - Average Waiting Time  
  - Average Turnaround Time  
  - Context Switch Count  
  - Fairness Standard Deviation  

---

## Tech Stack

| Component | Description |
|------------|-------------|
| Language | Python 3 |
| Libraries | Matplotlib, NumPy, ipywidgets |
| Algorithm | Genetic Algorithm |
| Environment | Jupyter / Google Colab |

---

## How to Run

1. Open the OptiCore notebook in **Google Colab**.  
2. Run all cells in sequence.  
3. Adjust the sliders and inputs to set:
   - Number of processes  
   - GA population size  
   - Number of generations  
   - Mutation rate  
4. Click **Run GA Optimizer** to evolve the best scheduling strategy.  
5. Use **Compare Baselines** to view the performance of traditional algorithms.

---

## Visualization

- **Bar Chart:** Compares average waiting and turnaround times across algorithms.  
- **Gantt Chart:** Displays task execution order and duration for the best schedule.

---

## Project Media

Include visuals such as:
- **Interface Screenshot** — *Interactive OptiCore dashboard for process input and GA tuning*  
- **Gantt Chart** — *Optimized CPU scheduling visualization*  
- **Performance Comparison Graph** — *Baseline vs optimized performance comparison*  

---

## Demo Video

A short (2–5 minute) demo showing:
- The idea and workflow  
- Interactive process configuration  
- GA optimization results  
- Visualization of metrics and Gantt charts  

---

## Colab Link

[**Open in Google Colab**]([YOUR_COLAB_LINK_HERE](https://colab.research.google.com/drive/14iPkY02G_-g00-JRIzFIzTJiz-UizSHs?usp=sharing))


---

<p align="center"><b>OptiCore</b> — Built to make scheduling smarter.</p>
