# Manufacturing Quality Control Analysis

## Project Overview
This project analyzes manufacturing production data to monitor product quality, identify defect factors, and improve manufacturing processes. It includes exploratory data analysis, statistical process control, and predictive modeling using machine learning.

## Dataset
The dataset contains measurements of production variables such as temperature, pressure, humidity, product dimensions, defect counts, and quality scores for manufacturing batches.

## Analysis Steps

### 1. Data Loading and Exploration
- Loaded production dataset and inspected feature distributions and quality outcomes.
- Checked for imbalances in Pass/Fail classification.

### 2. Visualizations
- **Quality Score Distribution:** Histogram with KDE to understand variance in quality.
- **Defect Count by Product Line:** Box plots showing defect trends across production lines.
- **Average Defect Count by Shift:** Bar charts comparing defect averages per shift.
- **Correlation Heatmap:** Displays relationships between numeric features for insight on multicollinearity.

### 3. Feature Encoding
- Encoded categorical variables (product line, shift, material grade) for machine learning compatibility.

### 4. Modeling
- Selected relevant features and split data into training and testing sets.
- Trained a Random Forest classifier to predict Pass/Fail quality outcome.
- Evaluated model performance with precision, recall, F1-score, and accuracy metrics.

### 5. Feature Importance
- Visualized feature importance to discover which variables most influence product quality.

## Technologies Used
- Python libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
- Jupyter Notebook / Google Colab

