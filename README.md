# ndvi-land-cover-classification-summer-analytics-2025
NDVI-based land cover classification using logistic regression for Summer Analytics 2025. Handled noisy satellite time-series data with imputation, scaling, and feature engineering. Achieved 79.09% accuracy, ranked 272/791.

NDVI Land Cover Classification – Summer Analytics 2025 Hackathon

This project solves a real-world satellite image classification problem using NDVI (Normalized Difference Vegetation Index) time-series data. The task was part of the Summer Analytics 2025 hackathon organized by IIT Guwahati in collaboration with GeeksforGeeks.

📂 Dataset
Train.csv
Test.csv

Target classes: Water, Farm, Forest, Grass, Orchard, Impervious

Train/Test split provided separately

Missing values due to cloud cover and noise

🎯 Objective
Predict land cover types (e.g., forest, farm, water, orchard, grass, impervious) using NDVI time-series values derived from satellite imagery.

Key Highlights:

🛰️ Preprocessed noisy NDVI satellite data with missing values

🧼 Implemented mean/median-based imputation & time-series interpolation

⚙️ Applied logistic regression (as per rules) with feature scaling

📊 Engineered statistical and temporal features to improve classification

🏆 Achieved 79.09% accuracy and ranked 272 out of 791 participants

Technologies Used:
Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Jupyter Notebook

Missing values (NaNs)

Seasonal variation

Noisy observations

🛠️ Techniques Used
✅ Mean-based imputation (better than median for this dataset)

✅ StandardScaler for normalization

✅ NDVI feature engineering (mean, std, min, max, range)

✅ Logistic Regression (multi-class, scikit-learn)

✅ Submission in proper CSV format

🧪 Result
Metric	Value
Final Score	0.79096 (Public Leaderboard)
Rank	272 / 791 participants

📁 Files
notebook.ipynb – main training + submission notebook

submission.csv – final test predictions based on my 79% score this dataset is not the actual y_test values given in the competition

train.csv / test.csv – input data (not included, assumed provided)

📌 Learnings
NDVI is a powerful vegetation indicator but noisy in real data

Simple models like logistic regression can still perform well with the right preprocessing

Mean imputation worked better than expected — even with bimodal data

Combining scaled raw time-series with engineered features helped stabilize performance

📜 License
MIT License – feel free to use, fork, and learn from this work.
