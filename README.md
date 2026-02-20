# 🎓 Classmates Clustering using K-Means

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-orange.svg)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-red.svg)

This repository contains a machine learning class project focused on unsupervised learning. The goal was to collect behavioral and academic data from approximately 20 classmates and group them into 3 distinct clusters using the **K-Means** algorithm.

## 📝 Project Overview

In this project, a custom dataset was built based on personal subjective evaluations of classmates across five specific features. By applying K-Means clustering, the algorithm autonomously discovers hidden patterns and groups students with similar academic and social traits.

Since the data is 5-dimensional, **Principal Component Analysis (PCA)** was utilized to reduce the dimensionality to 2D, allowing for a clear and intuitive visual representation of the clusters.

## 📊 Dataset Features

Each classmate was evaluated and scored based on the following 5 criteria:

- `gpa (1-4)`: Academic performance.
- `communication (1-5)`: Interpersonal and communication skills.
- `activities (1-5)`: Participation in extracurricular or class activities.
- `discipline (1-5)`: Punctuality and behavioral discipline.
- `teamwork (1-5)`: Ability to work well in group projects.

## 🛠️ Tech Stack & Libraries

- **pandas** & **NumPy**: For data manipulation and aggregation.
- **scikit-learn**: For implementing K-Means clustering and PCA.
- **Matplotlib**: For generating high-quality visualizations (scatter plots, centroids, and cluster boundaries).

## 🚀 How to Run

1. Clone this repository to your local machine:

   ```bash
   git clone [https://github.com/yourusername/classmates-clustering.git](https://github.com/yourusername/classmates-clustering.git)
   cd classmates-clustering
   ```

2. Ensure you have the required dataset (`dataset.csv`) in the root directory. The CSV should have columns matching the features listed above, plus a `name` column.
3. Install the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib

```

4. Run the main script:

```bash
python main.py

```

## 📈 Outputs & Results

When you run the script, it generates two main outputs:

1. **2D Scatter Plot (PCA View):** A clear visualization showing the 3 distinct groups, the position of each classmate, the centroids, and the cluster boundaries.
2. **Cluster Analysis Table:** A terminal output displaying the mean values of each feature for the 3 groups, making it easy to interpret the "persona" of each cluster (e.g., the "Highly Academic" group vs. the "Socially Active" group).

## 🖼️ ScreenShot

![output](\screenshot\output.png)
