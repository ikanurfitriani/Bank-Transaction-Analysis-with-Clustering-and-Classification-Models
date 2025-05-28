# Bank-Transaction-Analysis-with-Clustering-and-Classification-Models

Bank Transaction Analysis with Clustering and Classification Models is a comprehensive machine learning project designed to analyze bank transaction data and uncover meaningful insights about customer behavior. This project combines unsupervised and supervised learning techniques to perform customer segmentation and classification, offering strategic value for financial institutions.

## 🔍 Objective
The primary goal is to:
- Segment bank customers based on transaction behavior using clustering.
- Build classification models to predict customer segments based on historical data.
- These insights can be used by banks to tailor marketing strategies, personalize services, and support data-driven business decisions.

## 📊 Clustering (Customer Segmentation) <br>
In the clustering phase, the K-Means algorithm is applied to numerical features such as:
- Customer age
- Transaction duration
- Account balance
- Transaction amount

The clusters are visualized using PCA (Principal Component Analysis) to simplify interpretation. Descriptive analysis follows to understand the profile of each cluster (e.g., high-value customers, low engagement users, etc.).

## 🤖 Classification (Customer Category Prediction) <br>
The clusters generated earlier are used as labels to train classification models, including:
- Decision Tree
- Random Forest

<br>The classification models aim to predict a customer's segment using historical features. Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score 

Hyperparameter tuning is also performed, particularly to optimize the Random Forest classifier.

## 🧹 Data Preprocessing <br>
Before modeling, the dataset undergoes several preprocessing steps:
- Normalization to scale numerical values
- Encoding of categorical variables
- Binning to convert continuous variables into categories when needed

## 💾 Model Saving <br>
Trained models are saved using joblib in .h5 format, making them reusable for future analysis or deployment.

## Directory Structure
```bash
Bank-Transaction-Analysis-with-Clustering-and-Classification-Models/
│
├── PCA_model_clustering.h5                 
├── Clustering_Submission_Akhir_BMLP_Ika_Nurfitriani.ipynb 
├── Klasifikasi_Submission_Akhir_BMLP_Ika_Nurfitriani.ipynb  
├── data_clustering.csv      
├── data_clustering_inverse.csv
├── decision_tree_model.h5
├── explore_RandomForest_classification.h5
├── model_clustering.h5
├── tuning_classification.h5
└── README.md
```

## Author
[@Ika Nurfitriani](https://github.com/ikanurfitriani)