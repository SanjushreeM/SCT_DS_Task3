# SCT_DS_Task3
# 📊 Task 03 – Decision Tree Classifier for Customer Purchase Prediction

## 📌 Project Overview

This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on demographic and behavioral data.  
The model is trained using a marketing dataset for classification.

The objective is to:
- Load and preprocess customer data  
- Train a Decision Tree model  
- Predict customer purchase decisions  
- Evaluate model performance  

---

## 🗂️ Dataset

**Dataset:** Marketing / Bank Customer Dataset (provided as archive.zip)

The dataset contains customer attributes such as:
- Age  
- Job  
- Marital status  
- Education  
- Contact type  
- Campaign details  
- Previous marketing outcomes  

**Target Variable:**  
`y` → Indicates whether the customer subscribed to the product  
- `yes` → Customer purchased  
- `no` → Customer did not purchase  

---

## ⚙️ Technologies Used

- Python (2.2.2)
- Pandas (1.26.4) 
- Scikit-learn (1.5.0)
- Matplotlib (3.9.0) 

---

## 📁 Project Structure

Task-03-DecisionTree/
│
├── archive.zip              # Dataset ZIP file
├── decision_tree.ipynb      # Jupyter Notebook / Python Script
├── README.md                # Project Documentation
└── requirements.txt         # Required Python Libraries

---

## 🚀 How to Run the Project

**Clone the Repository**

git clone <your-github-repository-link>
cd Task-03-DecisionTree

**Install Required Libraries**

pip install -r requirements.txt

**Place Dataset**

Ensure archive.zip is in the project folder.

**Run the Program**

- If using Jupyter Notebook:
jupyter notebook SCT_DS_Task3.ipynb

---

## 🔄 Process Workflow

1. Extract dataset from ZIP file
2. Load CSV file automatically
3. Encode categorical variables
4. Split data into training and testing sets
5. Train Decision Tree Classifier
6. Evaluate accuracy and classification report
7. Visualize Decision Tree

---

## 📈 Output

- Model Accuracy Score
- Classification Report
- Decision Tree Visualization

---

## ✅ Results

The Decision Tree model successfully predicts customer purchase behavior based on input features.
Performance is evaluated using accuracy and classification metrics.

