# 🛍️ Mall Customer Segmentation using KMeans

This project demonstrates customer segmentation using the KMeans clustering algorithm on the Mall Customers dataset. The objective is to group customers based on their characteristics to identify meaningful customer segments.

---

## 📌 Project Overview

Customer segmentation is an important business strategy used to understand customer behavior. In this project, I applied unsupervised machine learning (KMeans Clustering) to group customers into distinct clusters based on their features.

---

## 📂 Dataset

The dataset used is **Mall_Customers.csv**, which contains information such as:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

---

## 🔍 Steps Performed

1. Imported required libraries (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)
2. Loaded and explored the dataset
3. Checked for missing values and duplicates
4. Performed data preprocessing
5. Encoded categorical variable (Gender) using Label Encoding
6. Used the **Elbow Method** to determine optimal number of clusters
7. Applied KMeans clustering
8. Predicted cluster labels
9. Merged cluster results with original dataset
10. Analyzed number of customers in each cluster

---

## 📊 Elbow Method

The Elbow Method was used to find the optimal value of K by plotting WCSS (Within Cluster Sum of Squares). Based on the graph, the optimal number of clusters was selected.

---

## 🤖 Model Used

- **KMeans Clustering**
- Initialization method: k-means++
- Clusters selected: 2

---

## 📈 Results

The model successfully segmented customers into clusters. The final dataset includes an additional column:

- `Cluster Number`

Cluster distribution was analyzed using value counts.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run

1. Clone this repository
2. Install required libraries:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook
4. Run all cells

---

## 🎯 Learning Outcome

This project helped me understand:
- Unsupervised Machine Learning
- KMeans Clustering
- Elbow Method
- Data preprocessing techniques
- Customer segmentation strategy

---

## 📌 Future Improvements

- Try different numbers of clusters
- Add data visualization for better cluster interpretation
- Apply scaling before clustering
- Compare with other clustering algorithms

---

⭐ If you found this project helpful, feel free to star the repository!
