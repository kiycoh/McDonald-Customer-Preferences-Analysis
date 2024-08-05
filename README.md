# **McDonald's Customer Preferences Analysis**

This repository contains a comprehensive data analysis project on McDonald's customer preferences. The analysis, conducted using Python and Jupyter Notebook, aims to segment the customer base of McDonald's into distinct groups based on their preferences and characteristics. This segmentation helps tailor marketing strategies and product offerings to better meet the needs of different customer segments.

## **Objectives**

1. **Principal Component Analysis (PCA)**: Reduce the dimensionality of the data to identify the key features that explain the most variance.
![Pasted image 20240617143810](https://github.com/user-attachments/assets/9d7803a6-025f-41c6-b6ff-e2ffd3718bf5)

2. **K-Means Clustering**: Group customers into clusters based on their preferences.
![Pasted image 20240617143900](https://github.com/user-attachments/assets/ed5de3d0-1f40-4c05-8ff9-3fe76495ee43)

3. **Hierarchical Clustering**: Further refine the customer segments for deeper insights.
![Pasted image 20240617143909](https://github.com/user-attachments/assets/997160ab-8a0f-4d08-8fd7-7141fe87fcc7)


## **Techniques and Libraries Used**

- **Data Manipulation**: pandas, numpy
- **Data Visualization**: matplotlib, seaborn
- **Machine Learning**: sklearn, scipy
- **Clustering**: KMeans, hierarchical clustering
- **Dimensionality Reduction**: PCA
- **Standardization**: StandardScaler
- **Cluster Validation**: silhouette_score

## **Dataset**

The dataset includes survey results from McDonald's customers, capturing demographic data (age and gender) and preferences (taste, convenience, healthiness, etc.). The analysis aims to identify significant relationships between these characteristics and customer preferences towards McDonald's products.

![Pasted image 20240617142944](https://github.com/user-attachments/assets/8ed2cbf0-a5ad-419a-905a-322134c56164)


### **Key Insights**

- **Customer Segments**: Identification of distinct customer segments based on eating habits and preferences.
- **Preference Correlations**: Discovery of correlations between different customer preferences and demographic features.
- **Marketing Strategies**: Insights to help McDonald's tailor marketing campaigns and product offerings to specific customer segments.

![Pasted image 20240617143739](https://github.com/user-attachments/assets/465d664d-79ae-41c0-b08f-17c22052de7f)


## **Usage**

1. **Data Loading**: Reading the dataset using pandas.
2. **Exploratory Data Analysis (EDA)**: Initial data inspection, handling missing values, and understanding data distribution.
3. **Preprocessing**: Converting categorical variables to numerical, scaling features, and applying PCA for dimensionality reduction.
4. **Clustering**: Applying K-Means and hierarchical clustering to segment customers.
5. **Visualization**: Creating visual representations of the data and clusters for better interpretation.

---

# **Getting Started**

1. **Run the analysis**: Open `McDonalds_Customer_Analysis.ipynb` in Jupyter Notebook and execute the cells.

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

*This repository aims to provide valuable insights for data scientists, marketers, and anyone interested in understanding customer segmentation and preferences using real-world data.*
