# python-ml-learning-lab

Hands-on Python machine learning experiments and data science notebooks covering regression, clustering, NLP, and visualization using NumPy, Pandas, Scikit-learn, and Seaborn.

## What's inside

This repo is a collection of Jupyter notebooks from a Python data science internship/practice journey. Each notebook focuses on a specific topic or dataset:

| Notebook | Topic |
|----------|-------|
| `numpy.ipynb` | NumPy array operations and basics |
| `pandas.ipynb` | Pandas dataframes, cleaning, and manipulation |
| `matplotlib.ipynb` | Data visualization with Matplotlib |
| `seaborn.ipynb` | Statistical visualization with Seaborn |
| `eda.ipynb` / `eda2.ipynb` | Exploratory data analysis |
| `linearregression.ipynb` | Simple linear regression |
| `linearregression2.ipynb` | Multiple linear regression |
| `decisiontree.ipynb` | Decision tree classification |
| `kmeans.ipynb` | K-Means clustering (Iris dataset) |
| `neuralnetworks.ipynb` | Neural networks intro |
| `nlp.ipynb` | Natural language processing basics |
| `nlpsentimentanalysis.ipynb` | Sentiment analysis |
| `sqlconnection.ipynb` | Connecting Python to SQL databases |
| `errorhandling.ipynb` | Error handling and debugging |
| `test.ipynb` | Practice/test notebook |
| `combined.ipynb` | Combined analysis across concepts |

Datasets used include student performance, Black Friday sales, Zomato restaurant data, customer data, and more.

## Tech stack

- Python 3
- NumPy — numerical computing
- Pandas — data manipulation
- Matplotlib — plotting
- Seaborn — statistical visualization
- Scikit-learn — machine learning models
- Jupyter — notebook environment

## Getting started

```bash
# Clone the repo
git clone https://github.com/dineshbalaks7/python-ml-learning-lab.git
cd python-ml-learning-lab

# Create and activate a virtual environment
python -m venv .venv
.venv\Scripts\activate   # Windows
# source .venv/bin/activate  # macOS/Linux

# Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

## Project structure

```
python-ml-learning-lab/
├── notebooks/           # Jupyter notebooks (*.ipynb)
├── data/                # Datasets (CSV, Excel) — excluded from git via .gitignore
├── .gitignore           # Ignores .venv, caches, data files
└── README.md
```

> Large data files (CSVs, Excel, images) and the virtual environment are not tracked in git — see `.gitignore`.

## License

This is a personal practice/learning repository. Feel free to use it as a reference for your own data science journey.

---
**Author:** Dinesh Bala KS
