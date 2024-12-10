# breast_cancer_detection
Machine learning algorithms in the detection of breast cancer analyze medical data for the presence of patterns that characterize cancerous conditions. The earlier the disease is detected, the better the chances of survival and effective treatment. This project will be implemented based on a structured pipeline that includes data preprocessing, building predic

**Process Breakdown**

1. **Dataset**
- **Source**: The dataset to be used is likely to be the Breast Cancer Wisconsin Dataset or similar.
- **Features**:
Features of the nuclei, specifically:
    Clump Thickness
    Uniformity of Cell Size
    Marginal Adhesion
    Single Epithelial Cell Size
    Bare Nuclei
    Bland Chromatin
    Normal Nucleoli
    Mitoses
- These are numeric data and are obtained from fine-needle aspiration tests.
- **Target Label**: 
  - `0`: Benign
  - `1`: Malignant

  2. **Data Preprocessing**
Before feeding data to the model, preprocessing is done:
- Cleaning missing values.
- Scaling features to a uniform measure.
- Splitting data into training and test sets to validate the model.

### 3. **Exploratory Data Analysis (EDA)**
- Visualizations such as histograms, scatter plots, and heatmaps are done to gain insights into the following: 
  - Correlation between features
  - Distribution of the cases - benign and malignant
  - Anomalies or outliers, if any

### 4. **Model Training**
- Classification of data is done using various machine learning algorithms. The commonly used models are: 
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Neural Networks
- Hyperparameter tuning for the improvement of model performance.

### 5. **Evaluation Metrics**
The efficiency of the model is given by the following:
• **Accuracy**: Overall correctness.
• **Precision**: Avoiding False Positives
• **Recall (Sensitivity)**: Find out true positives.
• **F1-Score**: Balance of precision and recall.

### 6. **Deployment (Optional)
If necessary, it may include designing a web or desktop interface that users can use to upload their data and get predictions from.
The deployment can be done on Flask, Django, or Streamlit.
