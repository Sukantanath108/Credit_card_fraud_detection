🔐 Credit Card Fraud Detection – Machine Learning Approach
A machine learning project focused on detecting fraudulent credit card transactions using supervised classification algorithms and advanced resampling techniques to handle severe class imbalance.

📊 Dataset
This project uses the publicly available dataset from Kaggle:
🔗 Credit Card Fraud Dataset[https://www.kaggle.com/code/gpreda/credit-card-fraud-detection-predictive-models/input]

🧠 Models Implemented
To build a fraud detection system, I implemented and compared the following supervised learning algorithms:

✅ Logistic Regression
🌳 Decision Tree Classifier
🌲 Random Forest Classifier

Each model was evaluated for its ability to accurately detect fraudulent activities in highly imbalanced financial data.

⚖️ Tackling Class Imbalance
Given that fraud cases are extremely rare compared to normal transactions, the dataset is highly imbalanced. I applied the following resampling strategies to improve model performance:

🔁 Oversampling the Minority Class
Duplicated fraud samples to increase representation.
✂️ Under-sampling the Majority Class

Reduced the number of normal transactions.
🧪 SMOTE (Synthetic Minority Oversampling Technique)
Generated synthetic minority samples to balance the data using interpolation between existing instances.

🎯 Objective
To develop a scalable and accurate fraud detection system capable of identifying anomalous patterns in transaction behavior, ultimately enhancing the security of financial systems.

🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn
Imbalanced-learn (for SMOTE)
Jupyter Notebook

💡 "In fraud detection, precision isn't optional—it’s essential. This project shows how machine learning can drive smarter, faster, and more secure financial systems."
