# Customer Segmentation with K-Means Clustering

### Project Overview
This project applies the **K-Means clustering algorithm** to segment a synthetic customer dataset. The goal is to identify distinct customer groups based on their purchasing behavior. This segmentation is a core task in marketing analytics, allowing businesses to create highly targeted strategies and improve customer relationship management.

### Dataset
The model is applied to a synthetic dataset that simulates customer behavior with features like `spending`, `purchase frequency`, and `age`. This dataset allows for the demonstration of unsupervised learning techniques to uncover hidden patterns without pre-existing labels.

### Methodology
1.  **Data Generation and Preprocessing:** A synthetic dataset is created to represent customer data. Key features are selected and then scaled using a `StandardScaler` to ensure all features contribute equally to the clustering process.
2.  **Optimal Cluster Selection:** The **Elbow Method** is used to determine the optimal number of clusters (K). This visual technique helps identify the point where adding more clusters no longer significantly reduces the within-cluster sum of squares.
3.  **K-Means Clustering:** The K-Means algorithm is applied to the scaled data with the optimal number of clusters determined in the previous step.
4.  **Cluster Analysis:** The resulting clusters are analyzed by examining the mean values of the original features. This provides actionable insights into the unique characteristics of each customer segment.

### Concluded Results
The project successfully segments the customer base into distinct groups. The analysis of these clusters reveals valuable patterns, such as a "High-Value" segment with high spending and a "Low-Engagement" segment with infrequent purchases. This project demonstrates proficiency in unsupervised learning, data preprocessing, and the ability to derive actionable insights from data.

### Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
