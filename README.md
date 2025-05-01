## 🧠 Customer Segmentation using Clustering (K-Means & Agglomerative)

This project implements a clustering-based machine learning approach using **K-Means** and **Agglomerative Clustering** to group social media users based on their **age** and **estimated salary**. The goal is to help businesses understand customer segments for **targeted advertising** and **campaign personalization**.

## 📁 Dataset

**Source**: `social.csv`
**Features Used**:
  - `Age`
  - `EstimatedSalary`
  - `Gender` (converted to numeric)
## 🧹 Data Preprocessing
- Handled missing values (if any)
- Scaled features using `StandardScaler`
- Encoded `Gender` for visualization

## 🤖 Machine Learning Algorithms

### K-Means Clustering
- Optimal clusters found using **Elbow Method** (k = 4)
- Users grouped based on scaled features

### Agglomerative Clustering
- Optimal clusters identified via **Dendrogram**
- Implemented with **Ward linkage** and **Euclidean distance**

## 📊 Deployment

- Visualized clusters using `Matplotlib`, `Seaborn`, and `Plotly`
- Applied **PCA** for 2D representation
- Displayed centroids and cluster boundaries


## ✅ Evaluation

- **Silhouette Score**: `0.52` (moderate separation)
- Analyzed cluster-wise mean `Age` and `EstimatedSalary`

## 🏁 Result

- Segmented users into **4 meaningful clusters**
- Delivered actionable insights for marketing strategies
- Included interactive and static visualizations

