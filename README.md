🧠 Decision Tree Classification on Synthetic Customer Data
📌 Project Overview

This project demonstrates how to use a Decision Tree Classifier (from scikit-learn) on a synthetic dataset representing customer demographics and behaviors to predict whether a customer is likely to purchase a product.
The dataset is generated artificially and includes features such as Age, Income, Gender, Browsing Time, and Clicked Ads. A decision tree model is trained to classify whether the customer makes a purchase.

🚀 Features

✅ Generate synthetic customer dataset
✅ Preprocess categorical data using one-hot encoding
✅ Train-Test Split for evaluation
✅ Train a Decision Tree Classifier (Entropy criterion)
✅ Evaluate performance with Accuracy & Classification Report
✅ Visualize the trained decision tree

📊 Dataset Description

The dataset is synthetically generated with 500 samples.

Feature	Description
Age	Age of customer (18–60 years)
Income	Annual income (₹20,000 – ₹1,20,000)
Gender	Male / Female
BrowsingTime	Time spent on website (1–60 minutes)
ClickedAds	Number of ads clicked (0–10)
Purchased (Target)	1 = Purchase, 0 = No Purchase

🛠️ Tech Stack

Python 3
Pandas – Data handling
NumPy – Numerical processing
Scikit-learn – Model building & evaluation
Matplotlib – Visualization

📌 Future Enhancements

Add feature importance plot
Use Random Forest Classifier for better performance
Hyperparameter tuning with GridSearchCV
Save model with joblib for deployment

👩‍💻 Author

Hasini.K
