# Prodigy_Infotech_MLprojects

## prodigy_task01.ipynb — Exploratory Data Analysis on House Prices Dataset

- **Libraries and Data Loading:** Imports pandas, numpy, matplotlib, seaborn, and suppresses warnings. Loads train and test datasets from CSV files.
- **Data Inspection:** Displays initial rows and examines dataset shape and detailed column info.
- **Missing Data Handling:** Identifies columns with missing values, summarizes their counts, and drops those columns to simplify analysis.
- **Data Summary:** Reassesses data structure post-cleaning and provides statistical summaries (mean, std, min, max, percentiles) for the remaining numerical columns.

**Purpose:**  
Demonstrates fundamental EDA techniques such as data loading, inspection, missing value treatment, and summarization. 

## prodigy_task02.ipynb — Customer Segmentation Using Mall Customers Dataset

1. **Data Loading and Preparation:**  
   Loads the dataset, renames columns for clarity, and performs initial data inspections (shape, types, descriptive stats).

2. **Exploratory Data Analysis (EDA):**  
   Visualizes the distribution of gender, detects outliers in 'Expense' and 'Income(k$)' via boxplots, and removes high-income outliers.

3. **Feature Selection:**  
   Drops non-essential columns ('Id', 'Sex') to retain 'Age', 'Income(k$)', and 'Expense' for clustering.

4. **Data Visualization:**  
   Uses scatterplots to explore relationships between 'Expense' and 'Income(k$)', including coloring by gender to confirm it does not affect clustering.

5. **Clustering:**  
   Applies KMeans with 5 clusters, predicts cluster membership, and adds cluster labels.

6. **Cluster Visualization:**  
   Displays clusters with scatterplots colored by identified groups.

**Purpose:**  
Provides a complete clustering workflow from raw data handling through to cluster visualization, 
enabling segmentation of customers based on spending and income patterns.

## prodigy_task03.ipynb — Handwritten Digit Recognition Using the MNIST Dataset

1. **Data Loading and Exploration:**  
   Imports relevant libraries, loads MNIST image and label data, checks dataset shape, and visualizes sample digits.

2. **Data Preprocessing:**  
   Normalizes pixel values to the [0,1] range and splits the data into training and testing sets.

3. **Model Building and Training:**  
   Implements a supervised learning model (e.g., logistic regression, SVM, or neural network) to classify digits, training on the training data.

4. **Evaluation and Visualization:**  
   Assesses model accuracy and visualizes performance through confusion matrices and example predictions.

**Purpose:**  
Illustrates a full supervised learning pipeline for image classification of handwritten digits.

## prodigy_task04.ipynb — Iris Flower Classification

1. **Data Loading and Exploration:**  
   Loads the Iris dataset, displays initial rows, and uses visualization tools like pairplots to explore feature distributions and relationships.

2. **Data Preprocessing:**  
   Ensures data cleanliness by checking for missing values and encodes species labels as needed.

3. **Model Building and Evaluation:**  
   Splits data into training and testing sets, applies classification algorithms (e.g., Logistic Regression, KNN, Decision Tree, SVM), and evaluates model accuracy.

4. **Visualization and Results:**  
   Presents predictions, performance metrics, and visualizations such as confusion matrices or decision boundaries.

**Purpose:**  
Demonstrates a canonical supervised machine learning workflow focused on multi-class classification of Iris species.

# Summary

Collectively, these notebooks provide clear examples of fundamental and intermediate data science workflows, covering:

- Data loading, cleaning, and exploratory analysis.
- Handling of missing data and outliers.
- Feature selection tailored to the analysis objective.
- Application of clustering and classification machine learning algorithms.
- Evaluation and visualization of models and clusters.
