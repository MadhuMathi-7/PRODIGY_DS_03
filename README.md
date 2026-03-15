📌 Task Objective
Build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.
This project is part of the Data Science Internship at Prodigy InfoTech.

📂 Dataset
The dataset used in this project is the Bank Marketing Dataset from the UCI Machine Learning Repository.
It contains customer information such as:
Age
Job
Marital Status
Education
Account Balance
Housing Loan
Personal Loan
Contact Communication Type
Campaign Details
Previous Marketing Outcomes

The target variable:
y
yes → Customer subscribed to the service
no  → Customer did not subscribe

⚙️ Technologies Used
Python
Jupyter Notebook
pandas
NumPy
scikit-learn
Matplotlib

🧠 Machine Learning Algorithm
The model used in this project is:
Decision Tree Classifier
A Decision Tree is a supervised machine learning algorithm used for classification and prediction tasks. It works by splitting the dataset into branches based on feature conditions until a prediction is made.

🔄 Project Workflow
1️⃣ Data Loading
The dataset is loaded using pandas.
2️⃣ Data Exploration
Understanding dataset structure using:
head()
shape
info()
3️⃣ Data Preprocessing
Checked for missing values
Converted categorical variables into numerical values using Label Encoding
4️⃣ Train-Test Split
The dataset is split into:
80% Training Data
20% Testing Data
5️⃣ Model Training
A Decision Tree Classifier model is trained using the training dataset.
6️⃣ Prediction
The trained model predicts whether a customer will purchase the product/service.
7️⃣ Model Evaluation
Model performance is evaluated using:
Accuracy Score
Classification Report
8️⃣ Decision Tree Visualization
The decision tree is visualized to understand how the model makes predictions.

📊 Output
The model predicts customer behavior based on their demographic and marketing campaign data.
Example prediction:
0 → Customer will not purchase
1 → Customer will purchase

The decision tree diagram shows how different features influence the final prediction.

📁 Project Structure
PRODIGY_DS_03
│
├── bank.csv
├── decision_tree.ipynb
├── README.md
└── requirements.txt

🚀 Learning Outcomes
Through this project, I learned:
Data preprocessing techniques
Handling categorical data
Training machine learning models
Decision Tree algorithm concepts
Model evaluation methods
Data visualization

