
# VPN vs Non-VPN Traffic Classification

This project focuses on classifying network traffic as VPN or Non-VPN based on time-based flow features using machine learning techniques.

## 📂 Files Included

- **VPN_Non_VPN.ipynb**: Jupyter Notebook containing data loading, preprocessing, model building, evaluation, and visualization.
- **TimeBasedFeatures-Dataset-15s-VPN.arff**: Dataset consisting of network traffic flow features collected over 15-second intervals.

## 🚀 Project Workflow

1. **Dataset Loading**: Import and load `.arff` file containing labeled network traffic features.
2. **Data Preprocessing**:
   - Handle missing or anomalous values.
   - Normalize/scale the feature set.
   - Encode categorical labels if required.
3. **Model Building**:
   - Train machine learning models (e.g., Random Forest, SVM).
   - Perform train-test split and cross-validation if needed.
4. **Evaluation**:
   - Compute accuracy, precision, recall, F1-score.
   - Plot confusion matrix and ROC curve.
5. **Visualization**:
   - Visualize model performance and important features.

## 🛠️ Requirements

Ensure the following Python libraries are installed:

```bash
pip install pandas numpy matplotlib scikit-learn scipy liac-arff
