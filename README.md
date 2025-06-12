Financial Anomaly Detection Project

This project focuses on identifying anomalies in financial transaction data using machine learning techniques. The dataset contains real-world inspired transaction details which help in training models to detect fraudulent or unusual activities.

📁 Dataset: `financial_anomaly_data.csv`

The dataset includes the following attributes:

- `timestamp` – The date and time of the transaction.
- `transactionID` – Unique identifier for each transaction.
- `account id` – Identifier for the account involved in the transaction.
- `amount` – Transaction amount.
- `merchant` – Name or code of the merchant where the transaction occurred.
- `transaction` – Type or description of the transaction.
- `location` – Geographical location of the transaction.

> ⚠️ Note: Ensure the dataset file is named correctly as `financial_anomaly_data.csv` when using in Google Colab or local environments.

📌 Objective

To build a model that identifies whether a transaction is normal or anomalous (potential fraud) based on historical transaction data.

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab
- GitHub
🚀 How to Use
1. Clone the Repository

git clone https://github.com/yourusername/your-repo-name.git

2. Open in Google Colab
You can open the notebook directly in Google Colab:

import pandas as pd

# Load from GitHub
url = 'https://raw.githubusercontent.com/nissysathwika/Anamoly-detection/main/financial_anomaly_data.csv'
df = pd.read_csv(url)
df.head()
Or, if uploading directly in Colab:


from google.colab import files
uploaded = files.upload()
df = pd.read_csv('financial_anomaly_data.csv')

3. Begin Analysis or Model Building
Start your preprocessing, visualization, and anomaly detection from here.

📈 Sample Tasks
Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Anomaly Detection using:

-Isolation Forest

-Decision Tree

-Autoencoders
