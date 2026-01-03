# 💳 Credit-Card-Fraud-Detection-Using-Machine-Learning

## ABSTRACT

Credit card fraud has emerged as one of the most critical challenges faced by the financial sector, resulting in substantial monetary losses each year. The rapid expansion of digital payment platforms has increased the complexity of detecting fraudulent transactions using traditional rule-based systems. Machine learning techniques offer an efficient approach by learning transaction patterns and identifying abnormal behavior in large-scale datasets.

Credit card fraud typically occurs due to unauthorized access to sensitive card information or misuse of an existing account. This project focuses on developing a machine learning-based system to detect fraudulent credit card transactions. Multiple models are trained on historical transaction data and evaluated on unseen data to assess their performance and robustness. A comparative study is conducted to identify the most reliable model for fraud detection.

<br>
<b>Keywords:</b> Credit Card Fraud Detection, Machine Learning, Imbalanced Data, Fraudulent Transactions, Logistic Regression, Random Forest, Decision Tree.

---

## Overview

The widespread use of credit cards for online and offline transactions has significantly increased the risk of fraudulent activities. Financial institutions process millions of transactions daily, making manual fraud detection impractical. Recent studies and reports highlight a continuous rise in identity theft and unauthorized credit card usage, emphasizing the need for automated and intelligent fraud detection systems.

Credit card fraud mainly occurs in two forms:

- Unauthorized transactions performed using stolen card details  
- Identity theft leading to misuse of an existing credit card account  

These challenges motivate the use of data-driven approaches. This project applies machine learning techniques to analyze transaction behavior and accurately distinguish fraudulent transactions from legitimate ones within a highly imbalanced dataset.

---

## Project Goals

The primary objective of this project is to accurately detect fraudulent credit card transactions while minimizing false positives to protect genuine customers. The project aims to evaluate the effectiveness of different machine learning models in handling real-world fraud detection challenges.

The key goals include:

- Understanding transaction patterns through exploratory data analysis  
- Handling severe class imbalance in fraud detection data  
- Implementing and training multiple machine learning models  
- Evaluating model performance using appropriate classification metrics  
- Identifying the most suitable model based on performance comparison  

---

## Data Source

The dataset used in this project was obtained from Kaggle and contains real-world credit card transaction data collected from European cardholders over a two-day period in 2013. The dataset consists of **284,808 transactions** with **31 features**, making it a realistic and challenging dataset for fraud detection tasks.

To ensure customer privacy, most features have been transformed using **Principal Component Analysis (PCA)**. The dataset includes the following key attributes:

- **Time:** Time elapsed between consecutive transactions  
- **Amount:** Transaction value  
- **Class:** Target variable (1 indicates fraudulent transactions, 0 indicates legitimate transactions)  

<br>
<b>Dataset Link:</b>  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Machine Learning Techniques Used

The following machine learning algorithms were implemented and analyzed in this project:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

These models were selected to compare simple linear models with tree-based ensemble methods and to evaluate their ability to detect fraud in highly imbalanced datasets.

---

## Future Work

Several enhancements can be made to further improve the system, including:

- Incorporating advanced ensemble techniques such as Gradient Boosting or XGBoost  
- Applying resampling techniques like SMOTE to better handle class imbalance  
- Deploying the trained model using Flask or FastAPI for real-time fraud detection  
- Integrating behavioral and geolocation-based features for improved accuracy  
- Performing hyperparameter tuning to optimize model performance  

---

## Conclusion

This project demonstrates how machine learning can be effectively applied to detect fraudulent credit card transactions in real-world scenarios. By training and evaluating multiple classification models, the study highlights the strengths of tree-based algorithms in handling complex transaction patterns. The results indicate that the Random Forest and Decision Tree models provide strong performance in identifying fraudulent transactions, making them suitable candidates for practical fraud detection systems. This project reinforces the importance of machine learning in improving financial security and customer trust.
