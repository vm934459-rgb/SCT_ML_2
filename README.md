# SCT_ML_2 - Customer Segmentation using K-Means

## Internship Task

Machine Learning Internship - SkillCraft Technology

### Task 02

Create a K-Means clustering algorithm to group customers of a retail
store based on their purchase history.

## Objective

The objective of this project is to segment retail customers into
different groups based on their annual income and spending behavior.

## Dataset

The project uses the Mall Customer Segmentation Dataset.

The dataset contains information about:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

## Features Used

For clustering, the following features were selected:

- Annual Income (k$)
- Spending Score (1-100)

These features provide a useful representation of customer purchasing
behavior.

## Machine Learning Algorithm

K-Means clustering was used for customer segmentation.

The Elbow Method was used to determine the appropriate number of
clusters. Based on the resulting curve, 5 clusters were selected.

## Results

The model successfully divided the customers into 5 groups based on
their income and spending behavior.

The resulting clusters can be interpreted according to their average
income and spending score, allowing different customer segments to be
identified.

## Visualizations

The project includes:

- Elbow Method plot
- Customer segmentation plot
- Cluster centroid visualization

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
SCT_ML_2/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── results/
│   ├── elbow_method.png
│   └── customer_segments.png
│
├── README.md
├── requirements.txt
└── .gitignore