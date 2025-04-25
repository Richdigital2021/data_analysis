# 🚢 Titanic Survival Prediction

This project analyses the **Titanic passenger dataset** to explore the factors that influenced survival during the shipwreck. It includes data preprocessing, visualisation, and machine learning model development to predict survival.

---

## 📁 Dataset Overview

The dataset contains information about the passengers on the Titanic, including:

- `PassengerId` – Unique ID  
- `Pclass` – Ticket class (1st, 2nd, 3rd)  
- `Name`, `Sex`, `Age` – Personal details  
- `SibSp`, `Parch` – Family aboard  
- `Ticket`, `Fare` – Ticket info  
- `Cabin`, `Embarked` – Cabin and port of embarkation  
- `Survived` – Target variable (1 = Survived, 0 = Did not survive)

---

## 🎯 Project Objectives

- Load and clean the Titanic dataset
- Handle missing values and categorical data
- Explore trends and relationships with visualisations
- Train machine learning models to predict survival
- Evaluate model performance with appropriate metrics

---

## 🛠️ Tools and Libraries Used

- **Python**  
- **pandas**
- **matplotlib**
- **seaborn**  
- **scikit-learn**
- **Jupyter Notebook**

---

## 📊 Key Visualizations

- Survival rate by gender and class
- Age distribution of survivors vs. non-survivors
- Correlation heatmap
- Fare vs. survival scatter plot
- Confusion matrix for model results

---

## 🤖 Models Trained

- Logistic Regression  
- Random Forest Classifier  
- K-Nearest Neighbours  
- Support Vector Machine

Model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC Curve

---

## 📊 Visualizations Included

- Histogram of features
- Pairplot of feature relationships
- Correlation heatmap
- Boxplots grouped by species
- Confusion matrix for classification results

---

## 📁 File Structure

titanic-survival/ 

├── titanic_train.csv # Training data 

├── titanic_test.csv # Test data (optional) 

├── titanic_analysis.ipynb # Main Jupyter Notebook 

├── README.md # Project documentation


---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/iris-analysis.git

2. Open the notebook:
   ```bash
   jupyter notebook titanic_analysis.ipynb

## 🧠 Insights & Findings
- Women and children had a significantly higher chance of survival.

- First-class passengers had higher survival rates than lower classes.

- Age, Fare, and Embarkation point also contributed to survival prediction.

## 📌 License
This project is licensed under the MIT License.

## 📬 Contact
For any questions or suggestions, reach out via akintunderichard28@gmail.com
