# Perceptron

Trains `sklearn.linear_model.Perceptron` on `data/placement.csv` (CGPA and resume score → placed/not placed) and plots the learned decision boundary with `mlxtend.plotting.plot_decision_regions`.

Run `perceptron.ipynb` top to bottom (needs `mlxtend` — see root `requirements.txt`).

Result: the perceptron finds a linear boundary that separates placed vs. not-placed students using just two features.

Following the CampusX 100 Days of ML / DL course.
