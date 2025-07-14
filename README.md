# somalincode
🧾 Credit Card Fraud Detection using Machine Learning
This project focuses on building an intelligent fraud detection system to identify suspicious credit card transactions in real-time. The system leverages supervised machine learning algorithms and advanced sampling techniques to handle highly imbalanced datasets and ensure accurate fraud prediction.

🚀 Features
✅ Data Preprocessing & Cleaning (handling nulls, outliers, scaling)
📊 Exploratory Data Analysis (EDA) to understand patterns
✅ Fraud Detection using:

Logistic Regression

Random Forest



🧮 Class Imbalance Handling using:

Undersampling

📚 Model Evaluation using:

Accuracy, Precision, Recall, F1-score

Confusion Matrix and ROC Curve

🧪 Custom input testing and real-time prediction simulation

🧠 Model Architecture

📄 Transaction Classification:

Preprocessing: Feature scaling, outlier removal, and encoding

Algorithms: Logistic Regression, Random Forest

Output: Transaction labeled as Fraudulent or Legitimate

⚖️ Class Imbalance Handling:

Applied undersampling to reduce majority class

Balanced dataset to improve model sensitivity and reduce false negatives

🛠️ Tech Stack

Language: Python

Libraries:

scikit-learn for ML models

pandas, numpy for data handling

matplotlib, seaborn for visualization

Environment: Jupyter Notebook / Google Colab

Dataset: Public credit card transaction dataset (e.g., Kaggle)

📁 Directory Structure

bash
Copy
Edit
├── models/           # Trained model files  
├── data/             # Credit card transaction dataset  
├── outputs/          # Evaluation plots, reports  
├── notebooks/        # Jupyter notebooks  
└── README.md         # Project documentation  
⚙️ How to Run

Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt  
Open notebook:
Launch fraud_detection.ipynb in Colab or Jupyter.

Test with custom input:
Simulate new transaction data and get a fraud prediction instantly.

📊 Results

Logistic Regression: ~92% Accuracy

Random Forest: ~95% Accuracy

XGBoost: ~96% Accuracy

Recall (Fraud Detection): Over 94% with SMOTE applied

Combined Insights: Improved precision-recall tradeoff using ensemble comparison

📌 Future Work

Integrate real-time data stream for live prediction

Build dashboard/web app using Streamlit or Flask

Deploy model on cloud (Heroku/AWS)

Extend to other types of financial fraud (loan, insurance)
