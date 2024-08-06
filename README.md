# Bank Customer Churn Prediction

In the competitive landscape of modern banking, predicting customer churn is essential for maintaining client relationships. This study employs advanced machine learning techniques to analyze customer behavior and forecast the likelihood of clients leaving the bank.

**Technologies Used**: LightGBM - XGBoost - Random Forest 

## Bank Customer Churn Dataset:

The bank customer churn dataset, available on Kaggle, is widely used for predicting customer turnover in the banking sector. Initially comprising 12 features and a label, the dataset was expanded with 10 additional features, such as 'IsSenior,' 'ZeroBalance,' and 'IsActive_by_CreditCard,' resulting in 22 characteristics. It contains 165,034 entries, where 130,113 customers did not churn and 34,921 did, creating a significant class imbalance. This imbalance was addressed using SMOTE to enhance the performance of our predictive models.

<div align=center>
<img width="377" alt="Screenshot 2024-08-06 at 9 59 09 PM" src="https://github.com/user-attachments/assets/1a615d9c-4000-49b5-a26b-cb1f411b6290">
</div>

## Model Enhancement Techniques:

- Hyperparameter Tuning: Fine-tuning model parameters to improve accuracy.
  
- Feature Engineering: Adding informative features to enhance model performance.
  
- SMOTE-Based Upsampling: Addressing class imbalance to improve predictive accuracy.

## Evaluation Metrics:

- Accuracy Score: Ratio of correctly predicted instances to total instances.
  
- Confusion Matrix: Shows counts of True Positives, True Negatives, False Positives, and False Negatives.
  
- AUC Score: Represents model performance by plotting the true positive rate against the false positive rate.
  
- Precision: Ratio of true positives to total predicted positives.
  
- Recall: Ratio of true positives to actual positives.
  
- F1-Score: Harmonic mean of precision and recall.
  
<p align="center">
  <table>
    <tr>
      <td><img width="253" alt="Screenshot 2024-08-06 at 10 05 04 PM" src="https://github.com/user-attachments/assets/877fdfe0-17b8-4d9b-b1d5-b0b3f5074707"></td>
      <td><img width="260" alt="Screenshot 2024-08-06 at 10 05 22 PM" src="https://github.com/user-attachments/assets/573c1c03-a337-4fd1-8f4f-d3b680de79aa"></td>
      <td><img width="257" alt="Screenshot 2024-08-06 at 10 05 30 PM" src="https://github.com/user-attachments/assets/6509fc58-d986-4e2b-ae1d-807c7d31ca71"></td>
    </tr>
  </table>
</p>

## Results and Conclusion:

The tables below summarize the performance of three models—Random Forest, XGBoost, and LightGBM—using metrics such as precision, recall, F1-score, accuracy, and AUC. Table 1 presents the results for the Random Forest model, Table 2 covers the XGBoost model, and Table 3 highlights the LightGBM model, which delivered the best outcomes. These tables offer a comprehensive comparison of each model's effectiveness under different preprocessing techniques.

<div align=center>
<img width="325" alt="Screenshot 2024-08-06 at 10 08 02 PM" src="https://github.com/user-attachments/assets/530e5984-8651-4ace-9574-fe78777f723f">
</div>

The “Bank Churn Prediction” project predicts customer attrition to help banks retain clients. Using LightGBM, XGBoost, and Random Forest, the study addresses class imbalance by oversampling the minority class. LightGBM achieved the highest AUC of 88.88%. Future improvements include using K-fold cross-validation and ensemble methods to boost accuracy.

