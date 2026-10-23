# ml-practice

Small ML/DL projects I build while learning, one folder each.

| Project | What it does | Key result / takeaway |
|---------|---------------|------------------------|
| [house-price-prediction](house-price-prediction/) | EDA and cleaning of the Bengaluru house price dataset; feature engineering (bedrooms, sqft per room, etc.) | Learned how messy real-world categorical/numeric columns get, and how to systematically clean them before modeling |
| [deep-learning/perceptron](deep-learning/perceptron/) | Trains a Perceptron on a toy placement dataset and visualizes the decision boundary | Saw how a linear model draws its decision boundary, and what `mlxtend.plotting.plot_decision_regions` needs to plot it |

## Setup

```
pip install -r requirements.txt
```

## Data

Datasets aren't committed. Each project reads from its own `data/` folder (ignored by git), so download the file and put it there before running the notebook:

| Project | File | Source |
|---------|------|--------|
| house-price-prediction | `data/Bengaluru_House_Data.csv` | "Bengaluru House Price Data" on [Kaggle](https://www.kaggle.com/datasets?search=bengaluru+house+price) |
| deep-learning/perceptron | `data/placement.csv` | Toy dataset from the CampusX course |

## Credit

Several projects follow along with the [CampusX](https://www.youtube.com/@campusx-official) 100 Days of Machine Learning / Deep Learning series — code in those notebooks was written while following that course.
