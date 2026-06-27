# NBA Shot Data Mining Project

## Project Overview

This project focuses on analyzing NBA shot data using Data Mining and Machine Learning techniques.

The goal of the project is to explore shooting patterns, clean and preprocess the dataset, perform exploratory data analysis, apply clustering algorithms to identify player shooting styles, and build classification models to predict shot outcomes.

---

## Dataset

The dataset contains NBA shot records with:

- 128,069 rows
- 21 columns

The data includes information about:

- Player details
- Game information
- Shot distance
- Shot type
- Shot zone
- Defender distance
- Shot result
- Game conditions

---

## Project Steps

## 1. Data Collection and Understanding

The dataset was loaded and analyzed to understand:

- Dataset structure
- Number of rows and columns
- Data types
- Statistical information
- Missing values

---

## 2. Data Cleaning

The cleaning process included:

- Detecting missing values
- Handling missing data
- Removing duplicate records
- Detecting and handling outliers

Techniques used:

- Mean value replacement for missing values
- Box plots for outlier detection
- IQR method and percentile clipping for outlier handling

---

## 3. Data Preprocessing

The preprocessing phase included:

- Converting categorical variables into numerical values
- Feature transformation
- Column renaming
- Splitting combined columns into separate features
- Date conversion

Examples of processed features:

- Shot result conversion
- Shot zone classification:
  - Close
  - Mid-Range
  - Three-Point
- Defender pressure classification:
  - Tight
  - Contested
  - Open

---

## 4. Exploratory Data Analysis (EDA)

Different visualizations and analyses were performed to understand shooting behavior.

The analysis includes:

- Shot distribution by zone
- Shooting percentage by player
- Shot distance distribution
- Defender pressure effect on shooting accuracy
- Made vs missed shot ratio
- Shooting percentage across different court zones
- Heatmap analysis of player shooting frequency

Libraries used:

- Matplotlib
- Seaborn

---

## 5. Player Clustering Using K-Means

K-Means clustering was applied to group players based on their shooting characteristics.

Features used for clustering:

- Shooting percentage
- Average shot distance
- Three-point attempt rate
- Average dribbles
- Average touch time

Steps:

1. Feature selection
2. Data scaling using StandardScaler
3. Applying K-Means algorithm
4. Visualizing clusters using PCA
5. Finding the optimal number of clusters using the Elbow Method

---

## 6. Classification Models

Machine learning classification models were built to predict shot outcomes.

Target:

- Field goal made or missed

Features:

- Shot distance
- Shot type
- Shot zone group
- Defender pressure

---

## Models Used

### Decision Tree Classifier

The Decision Tree model was trained and evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

### Random Forest Classifier

A Random Forest model was also implemented to improve prediction performance.

The model was evaluated using the same classification metrics.

Feature importance was analyzed to determine which factors have the strongest impact on shot outcomes.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Techniques

This project demonstrates:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- K-Means clustering
- PCA visualization
- Decision Tree classification
- Random Forest classification
- Model evaluation

---

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn missingno
```

3. Open the notebook:

```
data_mining_project.ipynb
```

4. Run the notebook cells sequentially.

---

## Project Goal

The main objective of this project is to apply Data Mining techniques to NBA shot data and discover meaningful patterns in player performance while building predictive models for shot success.

---

## Author

Your Name  
