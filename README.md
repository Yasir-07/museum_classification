# museum_classification
🏛️ Museum Image Classification - Supervised & Semi-Supervised Learning
📌 Project Overview
This project addresses the Museum Image Classification problem — distinguishing between museum-indoor and museum-outdoor images. The goal is to build and evaluate supervised models (Decision Tree, Random Forest, XGBoost) and a semi-supervised Decision Tree model using a self-training approach.

The entire code, including data loading, preprocessing, training, evaluation, and predictions, is contained within a Jupyter Notebook, making it easy to follow and demonstrate.

📊 Dataset Information
Dataset Source: MIT Places Dataset - Museums Subset

How to Obtain the Dataset:

Visit: http://places.csail.mit.edu/browser.html
Download images from these two categories:
museum-indoor
museum-outdoor
Arrange them into a folder called Dataset, like this:
Dataset/
├── museum-indoor/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
├── museum-outdoor/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── …


🏗️ Project Structure

📂 Repo/
├── Dataset/                     # Dataset (user needs to download manually)
├── Museum_Classification.ipynb  # Full code in Jupyter Notebook (training, evaluation, prediction)
├── models/                       # Trained models saved here (if applicable)
│   ├── decision_tree_model.joblib
│   ├── random_forest_model.joblib
│   ├── xgboost_model.joblib
│   ├── semi_supervised_dt_model.joblib
├── README.md                     # This file
├── requirements.txt              # List of libraries used
└── report.pdf                    # Final project report (3 pages)


📚 How to Run the Notebook
1️⃣ Install Required Libraries
Create a virtual environment (optional) and install dependencies:

pip install -r requirements.txt
2️⃣ Open the Notebook

jupyter notebook Museum_Classification.ipynb

