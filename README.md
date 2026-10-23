# ml-practice

Small ML/DL projects I build while learning, grouped by topic.

| Project | What it does | Key result / takeaway |
|---------|---------------|------------------------|
| [house-price-prediction](house-price-prediction/predictor.ipynb) | EDA and cleaning of the Bengaluru house price dataset; feature engineering (bedrooms, sqft per room, etc.) | Learned how messy real-world categorical/numeric columns get, and how to systematically clean them before modeling |
| [perceptron](deep-learning/perceptron.ipynb) | Trains a Perceptron on a toy placement dataset and visualizes the decision boundary | Saw how a linear model draws its decision boundary, and what `mlxtend.plotting.plot_decision_regions` needs to plot it |
| [nn_from_scratch](deep-learning/nn_from_scratch.ipynb) | Builds a small 2-4-1 neural network in NumPy on `make_moons` data: parameter initialization and forward pass (tanh hidden layer, sigmoid output) | In progress: forward pass works (17 trainable parameters, outputs in (0, 1)); training not added yet |

## Setup

```
pip install -r requirements.txt
```

## Data

Each notebook reads from a `data/` folder next to it. Most datasets aren't committed (`data/` is ignored by git), so download the file to the path below before running the notebook. The small datasets are included in the repo.

| Project | File | Source |
|---------|------|--------|
| house-price-prediction | `house-price-prediction/data/Bengaluru_House_Data.csv` | "Bengaluru House Price Data" on [Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data) |
| perceptron | `deep-learning/data/placement.csv` | Toy dataset from the CampusX course (included in the repo) |

## Credit

Several projects follow along with the [CampusX](https://www.youtube.com/@campusx-official) 100 Days of Machine Learning / Deep Learning series — code in those notebooks was written while following that course.
