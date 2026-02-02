TSP Optimization Using Genetic Algorithm (GA) and Particle Swarm Optimization (PSO)

This project implements and compares two optimization algorithms — Genetic Algorithm (GA) 
and Particle Swarm Optimization (PSO) — to solve the Travelling Salesman Problem (TSP) 
using Google Colab notebooks.

Both algorithms read TSP instances from a dataset, compute approximate shortest tours, 
and generate convergence plots.

------------------------------------------------------------
1. Files Included
------------------------------------------------------------
- TSP_GA.ipynb     — Google Colab notebook implementing GA
- TSP_PSO.ipynb    — Google Colab notebook implementing PSO
- tsp_dataset.csv  — Dataset containing multiple TSP instances
- README.txt       — Instructions for running the notebooks

------------------------------------------------------------
2. Requirements
------------------------------------------------------------
This project runs entirely in Google Colab, so no installation is required.

Colab already includes:
- Python 3
- Built-in Python libraries:
    random, math, csv, ast, time
- matplotlib (installed by default for plotting)

No additional installations are needed.

------------------------------------------------------------
3. How to Run the Notebooks
------------------------------------------------------------

-------------------------
Step 1 — Open in Colab
-------------------------
1. Go to https://colab.research.google.com/
2. Click File → Upload notebook
3. Upload either:
   - TSP_GA.ipynb
   - TSP_PSO.ipynb

-------------------------
Step 2 — Upload the Dataset
-------------------------
Each notebook contains the following code cell:

    from google.colab import files
    uploaded = files.upload()

When you run it:
1. A file upload window appears
2. Select tsp_dataset.csv
3. The dataset is loaded into the notebook environment

-------------------------
Step 3 — Run All Cells
-------------------------
After uploading the dataset:

1. At the top menu in Google Colab, click "Runtime"
2. Select "Run all"

Colab will then:
- Load the TSP dataset
- Initialize the GA or PSO algorithm
- Run the optimization
- Print:
    * Best tour found
    * Best tour distance
    * Execution time
- Display the convergence curve showing how the fitness improves over iterations

This completes the experiment.
