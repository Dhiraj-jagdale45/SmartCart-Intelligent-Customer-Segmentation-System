# SmartCart – Intelligent Customer Segmentation System

An unsupervised machine learning project that analyses e-commerce customer data to discover meaningful customer segments based on demographics, purchasing behaviour, website engagement, and customer loyalty indicators.

## Overview

SmartCart is a growing e-commerce platform with customer data collected across multiple countries. Its existing generic marketing approach does not account for differences in customer behaviour. This project explores customer segmentation to help identify groups with similar characteristics and support more targeted marketing and customer-retention strategies.

The project uses a dataset containing **2,240 customer records** and **22 attributes**.

## Objectives

- Explore customer demographics and purchasing patterns.
- Prepare and preprocess customer data for machine learning.
- Identify groups of customers with similar behaviour using unsupervised learning.
- Analyse the characteristics of the resulting customer segments.
- Derive insights that could support personalised marketing and customer-retention decisions.

## Dataset

The dataset contains customer-level information across the following categories:

| Category | Example attributes |
|---|---|
| Demographics | Year of birth, education, marital status, income |
| Household information | Number of children and teenagers at home |
| Purchase amount | Spending on wine, fruits, meat, fish, sweets, and gold products |
| Purchase frequency | Web, catalogue, store, and deal purchases |
| Engagement | Monthly website visits |
| Customer relationship | Enrollment date, recency of last purchase, complaints |

The dataset file included in this repository is `smartcart_customers.csv`.

## Repository Structure

```text
SmartCart-Intelligent-Customer-Segmentation-System/
│
├── smart_card_clustering_system.ipynb   # Data analysis and clustering notebook
├── smartcart_customers.csv              # Customer dataset
├── SmartCart Clustering System.pdf      # Project problem statement
└── README.md
```

## Tools & Technologies

- **Python** – Main programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Scikit-learn** – Machine learning and preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Experimentation and analysis

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Dhiraj-jagdale45/SmartCart-Intelligent-Customer-Segmentation-System.git
cd SmartCart-Intelligent-Customer-Segmentation-System
```

### 2. Install the required libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open `smart_card_clustering_system.ipynb` and run the cells in sequence.

## Project Workflow

1. **Data understanding:** Inspect the dataset, its attributes, data types, and distributions.
2. **Data preprocessing:** Prepare the data for analysis, including handling data-quality issues and transforming features where required.
3. **Exploratory data analysis:** Examine customer demographics, spending patterns, and purchasing frequency.
4. **Feature preparation:** Select and prepare relevant customer attributes for clustering.
5. **Customer clustering:** Apply unsupervised learning techniques to group customers with similar behaviour.
6. **Cluster analysis:** Compare the resulting groups and interpret their distinguishing characteristics.
7. **Visualization and insights:** Present patterns in the customer segments to support business interpretation.

## Expected Business Value

Customer segments can help an e-commerce business think beyond one-size-fits-all marketing. Depending on the patterns discovered, the analysis may support:

- More relevant promotions for different purchasing groups.
- Identification of high-spending or highly engaged customer groups.
- Better understanding of customers with low engagement or long purchase gaps.
- More focused customer-retention strategies.

These are potential applications of the analysis, not guaranteed business outcomes.

## Author

**Dhiraj Jagdale**

- GitHub: [Dhiraj-jagdale45](https://github.com/Dhiraj-jagdale45)

## Acknowledgement

This project was developed as an applied unsupervised machine learning exercise using the SmartCart customer segmentation problem statement.
