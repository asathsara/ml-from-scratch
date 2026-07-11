# Machine Learning From Scratch

A collection of machine learning algorithms implemented from scratch in Python to understand the core concepts, mathematics, and algorithms behind modern machine learning libraries such as Scikit-learn.

Instead of only using high-level APIs, this project focuses on building ML algorithms manually to develop a deeper understanding of how models learn patterns from data, make predictions, and evaluate performance.

## Goals

- Understand the internal workings of machine learning algorithms
- Practice implementing mathematical concepts using Python
- Learn how popular ML libraries abstract complex algorithms
- Build a strong foundation for advanced AI and ML topics

## Implemented Algorithms

### Supervised Learning

- Linear Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

### Unsupervised Learning

- K-Means Clustering
- Principal Component Analysis (PCA)

## Project Structure

The repository is organized as follows:

- **[from_scratch/](file:///D:/ai/ml-from-scratch/from_scratch/)**: Contains the mathematical implementations built completely from scratch using only NumPy and Matplotlib:
  - [01_linear_regression.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/01_linear_regression.ipynb)
  - [02_knn.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/02_knn.ipynb)
  - [03_decision_tree.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/03_decision_tree.ipynb)
  - [04_random_forest.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/04_random_forest.ipynb)
  - [05_kmeans.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/05_kmeans.ipynb)
  - [06_pca.ipynb](file:///D:/ai/ml-from-scratch/from_scratch/06_pca.ipynb)

- **Topic Directories** (in the root): Contain Scikit-learn references alongside their respective `.csv` datasets:
  - [01_linear_regression/](file:///D:/ai/ml-from-scratch/01_linear_regression/): Scikit-learn notebook & [housing_data.csv](file:///D:/ai/ml-from-scratch/01_linear_regression/housing_data.csv)
  - [02_knn/](file:///D:/ai/ml-from-scratch/02_knn/): Scikit-learn notebook & [classification_data.csv](file:///D:/ai/ml-from-scratch/02_knn/classification_data.csv)
  - [03_decision_tree/](file:///D:/ai/ml-from-scratch/03_decision_tree/): Scikit-learn notebook & [health_data.csv](file:///D:/ai/ml-from-scratch/03_decision_tree/health_data.csv)
  - [04_random_forest/](file:///D:/ai/ml-from-scratch/04_random_forest/): Scikit-learn notebook & [health_data.csv](file:///D:/ai/ml-from-scratch/04_random_forest/health_data.csv)
  - [05_kmeans/](file:///D:/ai/ml-from-scratch/05_kmeans/): Scikit-learn notebook & [customer_data.csv](file:///D:/ai/ml-from-scratch/05_kmeans/customer_data.csv)
  - [06_pca/](file:///D:/ai/ml-from-scratch/06_pca/): Scikit-learn notebook & [sensor_data.csv](file:///D:/ai/ml-from-scratch/06_pca/sensor_data.csv)

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Setup & Installation

To run this project on a new device:

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd ml-from-scratch
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   ```

3. **Activate the virtual environment:**
   - **Windows:**
     ```powershell
     .venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source .venv/bin/activate
     ```

4. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Learning Approach

Each algorithm includes:

- Concept explanation
- Mathematical intuition
- From-scratch implementation
- Example usage
- Comparison with Scikit-learn implementation

## Purpose

This repository is created for educational purposes to strengthen my understanding of machine learning fundamentals and bridge the gap between using ML frameworks and understanding the algorithms behind them.
