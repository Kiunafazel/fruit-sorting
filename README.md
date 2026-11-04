# Fruit Sorting 🍎

A beginner-friendly machine learning project that classifies fruits using numerical features such as mass, width, height, and color score.

## About the Project

This project uses a small fruit dataset containing measurements for different fruit categories. The data is explored and visualized, then used to train and evaluate classification models.

**Note:** This project performs classification from tabular measurements; it does not classify fruit images.

## Dataset

The dataset is stored in `fruit.txt` and includes:

- Fruit label and name
- Fruit subtype
- Mass
- Width and height
- Color score

## Workflow

1. Load and explore the dataset using Pandas.
2. Group the data by fruit name and inspect its dimensions.
3. Visualize feature relationships with a scatter matrix.
4. Select mass, width, height, and color score as input features.
5. Split the data into training and testing sets.
6. Scale the features with `MinMaxScaler`.
7. Train and evaluate classification models.

## Machine Learning Models

- Logistic Regression
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Structure

```text
fruit-sorting/
├── fruit-sorting.ipynb
├── fruit.txt
└── scatter_matrix.png
```

## Run the Project

Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

Open `fruit-sorting.ipynb` in Jupyter Notebook and run the cells.

## Purpose

This project was created for learning and practicing data exploration, visualization, feature scaling, and basic classification algorithms.
