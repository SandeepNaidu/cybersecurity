# Malware and Credit Card Fraud Detection Datasets

This repository provides information and commands to obtain two popular datasets used in cybersecurity and fraud detection: the Microsoft Malware dataset and the Credit Card Fraud dataset.

## Microsoft Malware Dataset

### **Description:**
The Microsoft Malware dataset consists of data about different machines, such as machine configurations, updates, and threat reports. The goal is to predict if a machine will soon be hit with malware.

### **Location:**
- [Microsoft Malware Dataset on Kaggle](https://www.kaggle.com/c/microsoft-malware-prediction/data)

### **Command to Download:**
First, ensure you have the Kaggle API set up. If not, follow the [official guide](https://github.com/Kaggle/kaggle-api#api-credentials).
  ```bash
  kaggle competitions download -c microsoft-malware-prediction
```

# Credit Card Fraud Detection Dataset

## **Description:**
The Credit Card Fraud Detection dataset contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred over two days, where we have 492 frauds out of 284,807 transactions. Each transaction is represented by features V1 through V28, which are the result of a PCA transformation. To maintain confidentiality, the original features are not provided. The 'Time' and 'Amount' features are not transformed data. The target variable is 'Class' where 1 indicates a fraudulent transaction and 0 indicates a genuine transaction.

## **Dataset Overview:**
- **Number of Instances:** 284,807
- **Number of Features:** 31 (including the target variable)
- **Fraudulent Cases:** 492
- **Genuine Cases:** 284,315

## **Location:**
- [Credit Card Fraud Detection on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## **Command to Download:**
```bash
kaggle datasets download mlg-ulb/creditcardfraud
