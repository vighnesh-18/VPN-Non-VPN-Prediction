
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
```

## 📈 Dataset Description

**Format** : ARFF (Attribute-Relation File Format).
**Features** : Time-based statistical features like:
Packet counts
Byte counts
Duration
Inter-arrival times
And 20 more..!

**Label** : VPN for encrypted traffic
            Non-VPN for unencrypted traffic

## 🎯 Objective
Develop an accurate and efficient classifier that can differentiate between VPN and Non-VPN traffic based on time-based characteristics without inspecting the packet payloads.

## 📚 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vighnesh-18/VPN-Non-VPN-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd VPN-Non-VPN-Prediction
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and execute the VPN_Non_VPN.ipynb notebook step by step.

