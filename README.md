# 🧠 Social Network Ads – Purchase Prediction
This project demonstrates a simple machine learning classification task using the *Social Network Ads* dataset from Kaggle.  
The goal is to predict whether a person will purchase a product based on their **Age** and **Estimated Salary**.

## I used two algorithms for comparison:

- K-Nearest Neighbors (KNN)
- Random Forest Classifier *(optional for further testing)*

## The project includes:

- Data loading and preprocessing using **pandas** and **scikit-learn**
- Model training and testing with **KNN**
- Feature scaling using **StandardScaler**
- Model evaluation (accuracy, confusion matrix, classification report)
- Visualization of error rates and decision boundaries
- Predictions on new customer data

---

🔧 **Technologies**
- Python  
- Scikit-Learn  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

📊 **Example Results**
The KNN model achieved the best performance around **k = 5–7**, with an accuracy of approximately **90%** (depending on the train/test split).  
Most buyers were older individuals with higher estimated salaries.

---

📂 **Dataset Information**

| Column | Description |
|--------|-------------|
| **User ID** | Unique identifier for each person |
| **Gender** | Gender (not used in model) |
| **Age** | Age of the person |
| **EstimatedSalary** | Estimated annual income |
| **Purchased** | Target variable (0 = Not Purchased, 1 = Purchased) |

Dataset source: [Kaggle – Social Network Ads Dataset](https://www.kaggle.com/rakeshrau/social-network-ads)

---

## 👤 Author
**Aktan Asanbaev**  
*Data & Process Analyst | Junior Machine Learning Engineer*  
📧 https://www.linkedin.com/in/aktan-asanbaev-84317b352/

---

📜 **License**
This project is free to use for learning and educational purposes.
