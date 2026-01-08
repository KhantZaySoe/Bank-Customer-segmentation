# Bank Customer Segmentation using Fuzzy C-Means

This project focuses on **segmenting bank customers into meaningful groups** using **Fuzzy C-Means clustering**, an unsupervised machine learning technique.
The goal is to help banks better understand customer behavior and improve marketing, retention, and service strategies.

---

##  Project Overview

Banks serve customers with different financial behaviors, balances, and activities. Instead of treating all customers the same, this project groups customers into **segments** based on their features.

Unlike traditional clustering (like K-Means), **Fuzzy C-Means (FCM)** allows a customer to belong to **multiple clusters with different degrees of membership**, which better reflects real-world customer behavior.

---

##  Objective

* Group customers based on their financial and personal attributes
* Identify customer patterns for:

  * Targeted marketing
  * Customer retention
  * Risk analysis
* Demonstrate use of **unsupervised learning (Fuzzy Clustering)**

---

##  Dataset

**File:** `Churn_Modelling.csv`
This dataset contains bank customer information such as:

* Credit Score
* Age
* Tenure
* Balance
* Number of Products
* Estimated Salary
* Geography
* Gender

The dataset is used **only for segmentation**, not prediction.

---

## Technologies Used

* **Python**
* **Pandas & NumPy** – data handling
* **Scikit-learn** – preprocessing
* **scikit-fuzzy** – Fuzzy C-Means clustering
* **Matplotlib / Seaborn** – visualization
* **Jupyter Notebook** – development environment

---

## Methodology

1. **Load Data**
   Read the bank customer dataset.

2. **Data Cleaning & Preprocessing**

   * Handle missing values
   * Encode categorical features (Gender, Geography)
   * Normalize numeric values for better clustering

3. **Apply Fuzzy C-Means Clustering**

   * Set number of clusters
   * Compute cluster centers
   * Assign each customer a **membership score** for each cluster

4. **Analyze Clusters**

   * Understand characteristics of each segment
   * Visualize customer groups

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Step 2: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scikit-fuzzy
```

### Step 3: Run the Notebook

```bash
jupyter notebook
```

Open:

```
Churn.ipynb
```

Run all cells from top to bottom.

---

##  Output

* Customer segments based on financial behavior
* Membership scores showing how strongly each customer belongs to each cluster
* Visual plots of cluster distributions

Example insight:

> Some customers show strong membership in high-balance clusters, while others belong partially to multiple groups, indicating mixed financial behavior.

---

##  Why Fuzzy C-Means?

Traditional clustering assigns each customer to **only one group**.
However, real customers may behave like **multiple types at once**.

Fuzzy C-Means:

* Allows **partial membership**
* Produces more realistic segmentation
* Useful for marketing and decision-making

---

##  Author

**Khant Zay Soe**
HND Computing Student | Machine Learning & Data Analysis Enthusiast


