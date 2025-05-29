# MACHINE-LEARNING-MODEL-IMPLEMENTATION

Company : CODTECH IT SOLUTIONS

Name : Chekuri Jayasri

Intern ID : CT06DA115

Domain Name : Python

Duration : 6 weeks

Mentor : Neela Santosh Kumar

Description : The provided Python script is a complete machine learning pipeline designed to predict whether a credit card has appeared on the dark web based on various features. It begins by verifying the existence of the dataset and loading it using pandas. The script then performs essential data cleaning steps such as dropping irrelevant or sensitive columns (e.g., IDs and card numbers), converting the credit_limit field to a numeric type, and parsing date fields like expires and acct_open_date to extract year information. Categorical variables are encoded using LabelEncoder, and missing values are implicitly handled during preprocessing. The target variable for classification is card_on_dark_web, and the dataset is split into training and test sets using an 80/20 ratio. Before training, feature scaling is applied using StandardScaler to normalize the data. A RandomForestClassifier is then trained on the scaled features. Model performance is evaluated using accuracy and a classification report, providing insights into precision, recall, and F1-score. The script is well-structured and can be extended with additional metrics like confusion matrix, class distribution, and model saving using joblib. It represents a robust foundation for a predictive system aimed at detecting compromised credit cards through supervised learning.
