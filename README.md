# 🚢 Titanic Survival Prediction using Logistic Regression

This project predicts whether a passenger survived the Titanic disaster using a Logistic Regression model trained on key features such as class, age, sex, and fare.

It includes:
- A **command-line version** to enter custom inputs
---

## 📁 Dataset

The dataset used is the [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)  
---

## 🔍 Features Used for Prediction

- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Gender of the passenger
- `Age`: Age in years (missing values filled with mean)
- `Fare`: Fare paid for the ticket

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- scikit-learn

---

## 🚀 How to Run the Project

### 🖥️ 1. Run in Command-Line Interface (CLI)

#### 🔧 Setup

pip install pandas numpy scikit-learn
---
python titanic_predictor.py

---
## 🧪 Example Input & Output

### ▶️ Input:

--- Titanic Survival Predictor ---
Enter Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd): 3
Enter Sex (male/female): female
Enter Age: 22
Enter Fare Paid: 7.25

### ✅ Output:

🎉 The passenger would have SURVIVED!


---

### ▶️ Another Example Input:

Enter Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd): 2
Enter Sex (male/female): male
Enter Age: 40
Enter Fare Paid: 15.5
### ❌ Output:
😢 The passenger would NOT have survived.
