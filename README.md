# 🤖 Machine Learning

A collection of machine learning labs, exercises, and mini-projects covering classic algorithms and deep learning, implemented in Jupyter notebooks using scikit-learn, TensorFlow/Keras, and pandas.

This repository is a learning/coursework archive rather than a single application — each folder is a self-contained notebook exploring a different ML concept, algorithm, or dataset.

## Contents

| Path | Topic | Description |
|---|---|---|
| `KNN-Classification.ipynb` | K-Nearest Neighbors | A basic KNN classification example on a small synthetic dataset (20 training / 5 testing samples). |
| `Polynomial_Regression.ipynb` | Polynomial Regression | Fits polynomial regression curves (including a degree-5 example) to a small dataset and plots the results against linear regression. |
| `Lab/Fifa_Worldcup.ipynb` | K-Fold Cross Validation & World Cup Prediction | Demonstrates manual k-fold cross-validation (visualized with `KNeighborsClassifier` on the Iris dataset), then applies K-Fold CV to predict football World Cup match outcomes using `worldcup_data.csv`. Includes a saved results plot (`worldcup_prediction_results.png`). |
| `Lab-3/` | Image Classification (Cats vs Dogs) | Contains labeled image datasets (`cats_set/`, `dogs_set/`, 500 images each) intended for a cat-vs-dog image classification exercise. The notebook (`Untitled.ipynb`) is currently empty/in progress. |
| `Lab-4/CNN.ipynb` | Convolutional Neural Network | Builds and trains a CNN (using `tensorflow.keras`) on the Fashion MNIST dataset, with `Conv2D`, `MaxPooling2D`, `Flatten`, and `Dense` layers. |
| `IPL 2026 Prediction using ML/` | IPL Match Prediction | Contains `matches.csv` (historical IPL match data: teams, venues, toss results, winners, etc.) intended for a match-outcome prediction notebook. The notebook (`ipl_wow_facts.ipynb`) is currently empty/in progress. |

## Tech Stack

- **Language:** Python (Jupyter Notebooks)
- **Core libraries:** numpy, pandas, matplotlib
- **Machine Learning:** scikit-learn (KNN, K-Fold CV, Linear/Polynomial Regression)
- **Deep Learning:** TensorFlow / Keras (CNNs)

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or JupyterLab

### 1. Clone the repository

```bash
git clone <repo-url>
cd Machine-Learning-main
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

No `requirements.txt` is included, so install the core packages directly:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Then open any of the `.ipynb` files listed above to run the cells.

## Notes

- Some notebooks (`Lab-3/Untitled.ipynb`, `IPL 2026 Prediction using ML/ipl_wow_facts.ipynb`) are placeholders with datasets already in place but no analysis written yet.
- `.ipynb_checkpoints/` folders are Jupyter's autosave directories and can be safely ignored or deleted.
- Datasets included: `worldcup_data.csv` (FIFA World Cup match stats), `matches.csv` (IPL match history), and the `cats_set` / `dogs_set` image folders.

## License

No license specified. Add one if you plan to distribute this project.
