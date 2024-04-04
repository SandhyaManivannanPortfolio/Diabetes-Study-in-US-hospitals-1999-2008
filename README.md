**Diabetes Study in US Hospitals (1999-2008) 🌟🩺📊**

**Overview** The Diabetes 130-US hospitals for years 1999-2008 dataset provides a comprehensive view of diabetic patients experiences within U.S. hospitals. Spanning a decade and encompassing 130 hospitals, this dataset offers valuable insights into diabetes management, readmission patterns, and healthcare protocols.
The dataset was taken from UC Irvine and can be found at the following link: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008.

**Key Insights and Analyses**

**1. Data Preparation** To ensure quality of data, invalid entries (‘?’ and ‘Unknown/Invalid’) were handled, and columns like ‘weight,’ ‘medical_specialty,’ and ‘payer_code’ were removed.
Missing values were replaced with NaN, resulting in a refined dataset.

**2. Regression Analysis**

**Decision Tree Classifier:**
Achieved a test accuracy of 0.47, indicating slight improvements over random chance.
Precision, recall, and F1-score values were low, highlighting challenges in distinguishing between classes.
Overfitting on the training set emphasized the need for optimization strategies.
Feature importance analysis revealed influential features related to readmission.

**3. Clustering Analysis**

**K-Means Clustering:**
Identified natural groupings within the data.
Six well-defined clusters revealed nuanced relationships.
PCA analysis unveiled influential features related to medication changes, gender, and health indicators.
Model evaluation emphasized the dataset’s complexity and the need for K-Means.

**Recommendations**
Incorporate **weight-related** data for a comprehensive understanding of health dynamics.
Explore additional variables or datasets to enhance predictive capabilities.
Consider **Random Forest** models for better handling of class imbalance.

