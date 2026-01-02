# Customer Segmentation using K-Means Clustering

This repository contains the code and analysis for a Machine Learning project that implements K-Means Clustering to group retail store customers based on their purchase history. This project was completed as part of an internship task at **Prodigy InfoTech**.

## 📄 Project Overview
Customer segmentation is a crucial technique in marketing and customer relationship management. By clustering customers into distinct groups, businesses can tailor their marketing strategies, improve customer service, and maximize profitability.

In this project, we utilize the **K-Means Clustering** algorithm to analyze a dataset of mall customers. The algorithm groups customers based on two key features:
* **Annual Income (k$)**
* **Spending Score (1-100)**

## 📊 Dataset
The dataset used for this project is the **Mall Customer Segmentation Data** available on Kaggle.
* **Source:** [Kaggle - Customer Segmentation Tutorial in Python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
* **File:** `Mall_Customers.csv`

## 🛠️ Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Pandas:** Data manipulation and analysis.
* **NumPy:** Numerical operations.
* **Matplotlib & Seaborn:** Data visualization.
* **Scikit-learn:** Machine learning (K-Means algorithm).

## ⚙️ Installation & Usage
1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/customer-segmentation-kmeans.git](https://github.com/your-username/customer-segmentation-kmeans.git)
    ```
2.  Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Download the dataset from the Kaggle link above and place `Mall_Customers.csv` in the project directory.
4.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5.  Run the cells to see the Elbow Method analysis and the final cluster visualizations.

## 📈 Results
The K-Means algorithm (using the Elbow Method) identified **5 distinct customer segments**:
1.  **Low Income, Low Spending**
2.  **Low Income, High Spending**
3.  **High Income, Low Spending**
4.  **High Income, High Spending** (Target Group)
5.  **Average Income, Average Spending**

## 🤝 Acknowledgements
Special thanks to **Prodigy InfoTech** for providing this opportunity to learn and apply Machine Learning concepts.

---
*Created by [Your Name]*
