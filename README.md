# PCA & t-SNE Wine Quality Analysis

## 📌 Overview
This project applies **Principal Component Analysis (PCA)** and **t-SNE** to the **Wine Quality dataset** from the UCI Machine Learning Repository. It visualizes the dimensionality reduction results and compares PCA vs. t-SNE in handling high-dimensional data.

## 🔧 Setup Instructions
### **1️⃣ Prerequisites**
Make sure you have Python 3 installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### **2️⃣ Running the Notebook**
1. Open **Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
2. Load **485-assignment-2.ipynb** and run all cells.

---

## 📊 Results
### **1️⃣ PCA Visualization**
- **2D Scatter Plot:** Shows the first two principal components.
- **3D Scatter Plot:** Displays three principal components with explained variance.

### **2️⃣ t-SNE Visualization**
- **2D Scatter Plot:** Captures local structure and clustering patterns.

### **3️⃣ PCA vs. t-SNE Comparison**
| Method  | Strengths | Weaknesses |
|---------|----------|------------|
| **PCA** | Preserves global structure, interpretable variance | Loses fine details |
| **t-SNE** | Captures local clusters, good for visualization | Computationally expensive |
