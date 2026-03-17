🚀 Online Shopper Intention Prediction (CatBoost)

Predict whether a website visitor will make a purchase using Machine Learning + CatBoost.
This project focuses on understanding user behavior through EDA, visualization, and gradient boosting.

📌 Project Overview

E-commerce businesses thrive on understanding user behavior.
In this project, we analyze session-level data to predict:

👉 Will a user generate revenue (purchase) or not?

We use:

📊 Advanced EDA (Exploratory Data Analysis)

📈 Visualizations (2D + 3D)

🤖 CatBoost Classifier (Gradient Boosting)

🧠 Key Features

✅ Handles categorical + numerical data efficiently
✅ Minimal preprocessing using CatBoost
✅ Rich visual insights using:

Scatterplots

Heatmaps

Boxplots

Barplots

3D Plotly Visualization 🚀

📊 Exploratory Data Analysis (EDA)

We explored patterns in user behavior using:

📌 Scatterplot → Relationship between PageValues & ExitRates

📌 Boxplot → BounceRates vs Revenue

📌 Barplot → Monthly purchase trends

📌 Heatmap → Feature correlations

📌 3D Plot (Plotly) → Multi-dimensional behavior visualization

🤖 Model Used
🔥 CatBoost Classifier

CatBoost is a powerful gradient boosting algorithm that:

Handles categorical variables automatically

Reduces overfitting

Requires less preprocessing

Provides high performance on real-world datasets

⚙️ Model Training

Train-Test Split: 80% / 20%

Algorithm: CatBoostClassifier

Loss Function: Logloss

📈 Results

✅ Strong predictive performance

✅ Clear behavioral insights

✅ Good classification metrics (Accuracy, Precision, Recall, F1 Score)

💡 Key Insights

✔️ Higher PageValues → Higher chance of purchase
✔️ High ExitRates & BounceRates → Lower conversions
✔️ Seasonal trends affect user buying behavior 📅

🛠️ Tech Stack

Python 🐍

Pandas, NumPy

Matplotlib, Seaborn

Plotly (3D Visualization)

Scikit-learn

CatBoost

📂 Project Structure
├── data/
│   └── online_shoppers_intention.csv
├── notebook/
│   └── Day18.ipynb
├── README.md

▶️ How to Run
# Install dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn catboost

# Run the notebook or script
🌟 Future Improvements

🚀 Hyperparameter tuning
🚀 Try XGBoost / LightGBM
🚀 Deploy as a web app
🚀 Add ROC Curve & Confusion Matrix

📌 Challenge

This project is part of:
👉 #50DaysOfMLChallenge (Day 18)

🤝 Connect With Me

If you liked this project:
⭐ Star the repo
📢 Share feedback
🤝 Let’s connect on LinkedIn

💬 “Data tells a story — you just need to visualize it right.”
