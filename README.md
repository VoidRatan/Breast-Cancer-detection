
# Breast Cancer Prediction

📘 **Description**

This repository contains a machine learning project aimed at predicting breast cancer diagnoses based on numerical features of cell nuclei. The goal is to classify whether a tumor is benign or malignant using data preprocessing, model training, and evaluation techniques.
## Dataset

The dataset used in this project is stored in a file named dataset.csv. It includes:

- Features (X): Numerical measurements of cell nuclei.

- Target (y): Binary labels representing tumor types:

   - `0`: Benign

   - `1`: Malignant


## 🛠️ Technologies Used
Before running the notebook, ensure you have the following Python libraries installed:
- numpy
- pandas
- matplotlib

Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib

```
## Project Workflow

1. Data Loading
- Load the dataset using Pandas.
- Split the data into features (X) and labels (y).

2. Exploratory Data Analysis (EDA)

- Inspect the dataset structure and basic statistics.

- Visualize distributions or correlations if necessary.

3. Data Preprocessing

- Split the dataset into training and testing subsets.

- Apply feature scaling to normalize the data.

4. Model Training

- Train a machine learning model (e.g., logistic regression, decision tree) on the training data.

5. Model Evaluation

- Evaluate the model’s performance using metrics such as accuracy, precision, recall.
## 🔧 Installation & Usage

1. Clone the Repository:

```bash
git clone https://github.com/VoidRatan/breast-cancer-prediction.git  
cd breast-cancer-prediction
```
2. Ensure the `dataset.csv` file is in the project directory.
 

3. Run the Jupyter Notebook:
Use Jupyter Notebook or JupyterLab to open and execute the notebook:

```bash
jupyter notebook Breast_Cancer.ipynb
```

4. Execute the notebook cells sequentially.
    
## Acknowledgements

The dataset used in this project is publicly available and commonly utilized for educational purposes in machine learning. Special thanks to the contributors of such datasets.

