# Vegetable Classification Based on Nutritional Content

This project aims to classify vegetables into categories such as **leafy**, **root**, or **fruit** using their nutritional features like Vitamin A, Vitamin C, and fiber content.


## Problem Statement

Given a dataset of vegetables with nutritional values, the task is to build a machine learning classification model that can accurately categorize a vegetable into its type (leafy, root, fruit, etc.).


## Dataset Features

- `vitamin_a`
- `vitamin_c`
- `fiber`
- `type` (Target variable)


## Methodology

1. Loaded and preprocessed the dataset
2. Used `RandomForestClassifier` from Scikit-learn
3. Performed an 80/20 train-test split
4. Evaluated model performance using:
   - Confusion matrix
   - Accuracy
   - Precision (macro average)
   - Recall (macro average)
   - Classification report


##  Technologies Used

- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn



##  Results

- **Accuracy**: ~25%
- **Precision**: ~18%
- **Recall**: ~23%
- Confusion matrix heatmap and classification report generated



##  Files in this Repository

- `vegetable_classifier.ipynb`: Jupyter Notebook containing all code and outputs
- `report.pdf`: Final report with explanation, code, screenshots, and results
- `README.md`: Description and structure of the project

##  Acknowledgements

- Dataset provided for academic use
- Libraries: [Scikit-learn](https://scikit-learn.org/), [Pandas](https://pandas.pydata.org/), [Seaborn](https://seaborn.pydata.org/)
