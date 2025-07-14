# 🚢 Titanic Survival Prediction using Logistic Regression

This project predicts whether a passenger survived the Titanic disaster using a Logistic Regression model trained on key features such as class, age, sex, and fare.<br>

It includes:<br>
- A **command-line version** to enter custom inputs<br>

## 📁 Dataset <br>

The dataset used is the [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) <br> 

## 🔍 Features Used for Prediction<br>

- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Gender of the passenger
- `Age`: Age in years (missing values filled with mean)
- `Fare`: Fare paid for the ticket



## ⚙️ Technologies Used<br>

- Python
- Pandas
- NumPy
- scikit-learn

---

## 🚀 How to Run the Project <br>

### 🖥️ 1. Run in Command-Line Interface (CLI)

#### 🔧 Setup <br>

1. pip install pandas numpy scikit-learn

2. python titanic_predictor.py

---
## 🧪 Example Input & Output<br>

### ▶️ Input:<br>

--- Titanic Survival Predictor ---<br>
Enter Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd): 3<br>
Enter Sex (male/female): female<br>
Enter Age: 22<br>
Enter Fare Paid: 7.25<br>

### ✅ Output:<br>

🎉 The passenger would have SURVIVED!<br>



### ▶️ Another Example Input:<br>

Enter Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd): 2<br>
Enter Sex (male/female): male<br>
Enter Age: 40<br>
Enter Fare Paid: 15.5<br>
### ❌ Output:<br>
😢 The passenger would NOT have survived.
