
# Bank Customer Churn Prediction 

## Overview 
This project focuses on predicting **customer churn** (the likelihood of a customer leaving a bank) using machine learning techniques. The aim is to analyze customer behavior and provide insights for banks to improve customer retention strategies, reduce churn rates, and enhance overall customer satisfaction.

### Key Insights 
- **Credit Score**: Customers with lower credit scores are more likely to exit the bank.
- **Geography**: Germany had the highest churn rate (32.44%), followed by Spain (16.67%) and France (16.15%).
- **Age Impact**: Older customers (over 50 years) have a higher likelihood of churning.
- **Balance & Tenure**: Customers with lower balances and shorter tenures are more likely to leave the bank.

### Machine Learning Models 
The following machine learning models were used to predict customer churn:
- **Decision Tree Classifier**: Accuracy of 78.55%
- **Logistic Regression**: Accuracy of 80.35%
- **Random Forest Classifier**: Accuracy of 80.45%

### Business Impact 
By predicting customer churn, banks can implement targeted retention strategies, such as:
- Personalized offers tailored to customers at risk of leaving.
- Special promotions based on geographic regions with high churn rates.
- Loyalty programs for customers with multiple products.

### Recommendations 💬
1. **Geography-Based Recommendations**:
   - Focus on region-specific promotions in high-churn areas like Germany, Spain, and France.
   
2. **Gender-Based Recommendations**:
   - Develop gender-specific financial products to improve retention for both male and female customers.
   
3. **Active vs Inactive Members**:
   - Re-engage inactive customers with exclusive offers and promotions.
   
4. **Product-Based Recommendations**:
   - Encourage customers with fewer products to diversify by offering discounts or bundle deals.

### Technologies Used 
- **Python**: For data analysis and machine learning.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning models.
- **Matplotlib & Seaborn**: For data visualization.
- **Looker Studio**: For creating interactive dashboards.

### Data Source 
The dataset used in this project contains customer information, including:
- Demographics (age, gender.)
- Financial details (balance, credit score, salary.)
- Product usage and customer status.


### Links 
- **Google Colab Notebook**:https://colab.research.google.com/drive/12w2QrXnilg1AlMwi4TTYhlKGmr7Bb_0d?usp=sharing
- **Looker Studio Dashboard**:https://lookerstudio.google.com/reporting/b1ecb6ee-b85c-4150-b29f-ffab78012260
### License 
This project is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.
