
# 🎯 Placement Prediction ML Model

This project is a simple Machine Learning model that predicts whether a student will be placed or not based on their **CGPA** and **IQ**.

## 🚀 Overview

- **Problem Statement**: Many students wonder if they are likely to get placed based on academic indicators like CGPA and cognitive scores like IQ. This ML model aims to provide a basic prediction (`Placed` or `Not Placed`) using these inputs.
- **Input Features**:
  - 📚 `CGPA`: Cumulative Grade Point Average
  - 🧠 `IQ`: Intelligence Quotient
- **Output**:
  - ✅ `1`: Placed
  - ❌ `0`: Not Placed

## 🛠️ Tools & Technologies Used

- Python 🐍
- pandas, numpy
- scikit-learn (for ML model)
- matplotlib / seaborn (for data visualization, optional)
- Jupyter Notebook or VS Code
  
---

## 📂 Project Structure

placement-predictor/

│

├── data/

│ └── placement_data.csv

│

├── model/

│ └── placement_model.pkl

│

├── placement_predictor.py

├── train_model.py

├── requirements.txt

└── README.md

---


## 📊 Dataset

A simple dataset containing three columns:

| CGPA | IQ | Placement |
|------|----|-----------|
| 8.5  | 120| 1         |
| 6.2  | 100| 0         |

> You can modify or expand this dataset as needed.

## 🧠 Model Training

We used a simple classification algorithm (e.g., **Logistic Regression** or **Random Forest**) to train the model.

**Steps**:
1. Load the dataset.
   
2. Preprocess the data (if needed).
   
3. Split into training and test sets.
   
4. Train the model using scikit-learn.
   
5. Save the trained model using `pickle`.
    
6. python train_model.py

---
🧪 How to Use

Clone this repo.

Install dependencies:

pip install -r requirements.txt

---
Run prediction:

python placement_predictor.py

---
You’ll be prompted to enter:

CGPA

IQ

The script will return:

Placed or Not Placed

---

📌 Example

Enter CGPA: 8.2  

Enter IQ: 130  

Prediction: ✅ You are likely to be placed!

---
✅ Future Improvements

Add more features (communication skills, internships, projects, etc.)

Build a web interface using Streamlit or Flask

Improve model accuracy with better data and tuning







