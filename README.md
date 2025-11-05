# DataScienceCourse6_Assignment2
**Application and Challenges of K-Means Clustering — DS PGC Course 6 Assignment 2**

---

## 📘 Assignment Overview
This assignment explores the **real-world applications, benefits, and challenges of the K-Means clustering algorithm**.  
It examines how businesses and industries apply clustering for insights, and discusses the algorithm’s limitations along with better alternatives for certain data types.

---

## 🧩 Tasks Summary
**Part 1 — Real-World Applications of K-Means**
- **Task 1: Real-World Scenario** —  
  Retail and e-commerce companies use **K-Means** for **customer segmentation**, grouping shoppers by purchase history, demographics, and spending patterns.  
  Each cluster (e.g., *budget buyers*, *loyal frequent shoppers*, *premium spenders*) enables targeted marketing and efficient inventory planning.  
  K-Means is ideal because it is **unsupervised**, scalable, and handles millions of records quickly.

- **Task 2: Benefits of Using K-Means** —  
  - Enables **data-driven marketing** by uncovering meaningful patterns from large datasets.  
  - Simplifies visualization by summarizing data into compact, interpretable clusters.  
  - Fast and computationally efficient, producing actionable insights within minutes.

---

**Part 2 — Challenges and Alternatives**
- **Task 1: Limitations of K-Means** —  
  - Sensitive to **initial centroid placement**, which may lead to inconsistent results.  
  - Assumes **spherical, equal-sized clusters**, making it unsuitable for irregular or overlapping data.  

- **Task 2: When Not to Use K-Means** —  
  Avoid K-Means for **spatial, geographic, or noisy datasets** where clusters have non-linear or irregular shapes.  
  For such scenarios, **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) performs better —  
  it identifies clusters of arbitrary shape, isolates outliers, and doesn’t require pre-specifying the number of clusters.

---

## 🧰 Tools & Concepts
- **Concepts:** Unsupervised learning, centroid initialization, Euclidean distance, K-Means++, DBSCAN.  
- **Libraries (for optional implementation):** `scikit-learn`, `pandas`, `matplotlib`, `seaborn`.  
- **Environment:** Jupyter Notebook / Google Colab.

---

## 📂 Files Included
- `DataScienceCourse6Assignment2.pdf` — Problem statement  
- `DataScienceCourse6Solution2.pdf` — Written solution report with explanations  

---

## 🧭 Key Takeaways
- K-Means excels in fast, large-scale clustering of structured numeric data.  
- Initialization sensitivity and spherical assumptions limit its use on complex data.  
- DBSCAN offers a robust alternative for non-spherical or noisy datasets.  

---

## 👤 Author
**Utkarsh Anand** — DS PGC Course 6 Assignment 2  
Internshala Placement Guarantee Program
