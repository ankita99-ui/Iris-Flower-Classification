# Iris Flower Classification

A beginner-friendly machine learning project that classifies iris flowers into three species using petal and sepal measurements.

| Species | Emoji |
|---------|-------|
| Setosa | 🌸 |
| Versicolor | 🌺 |
| Virginica | 🌼 |

## What this project does

- Loads the classic **Iris dataset** from Scikit-learn (150 flowers, 4 features)
- Explores and visualizes the data (EDA, plots, pair plot)
- Trains two classifiers: **K-Nearest Neighbors (K=5)** and **Decision Tree**
- Evaluates both models (accuracy, classification report, confusion matrix)
- Predicts species for new flowers from four measurements

## Tech stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Project structure

```
IRIS/
├── iris_flower_classification.ipynb   # Main tutorial notebook (8 steps)
├── requirements.txt                   # Python dependencies
├── README.md
└── .gitignore
```


## Notebook steps

| Step | Topic |
|------|--------|
| 1 | Load dataset |
| 2 | Explore data (EDA) |
| 3 | Visualize features |
| 4 | Train/test split (80/20) |
| 5 | Train KNN (K=5) |
| 6 | Train Decision Tree |
| 7 | Evaluate and compare models |
| 8 | Predict a new flower |

## Requirements

- Python 3.9 or newer recommended
- See `requirements.txt` for package versions

## Dataset

The Iris dataset is built into Scikit-learn (`sklearn.datasets.load_iris`). No separate download is needed.

**Features (cm):**

- Sepal length, sepal width
- Petal length, petal width

**Target:** species (setosa, versicolor, virginica)

## License

Educational project — use freely for learning.
