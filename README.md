# 🚢 Titanic Survival Prediction - Kaggle 0.77033

> Predicting survival on the Titanic — My first Kaggle competition

### 🏆 Score
**Kaggle Public Score: 0.77033**
- Model: Random Forest (300 trees)
- CV Score: 0.8033

### 📊 Result
![Result](result.png)

### 🧠 What I Did
- **Feature Engineering:** Title extraction from Name, FamilySize, IsAlone, Cabin letter
- **Missing Values:** Age by Title median, Fare median, Embarked mode
- **Encoding:** One-Hot Encoding for Sex, Embarked, Title, Cabin
- **Model:** RandomForestClassifier with 5-fold CV

### 🛠️ Tech Stack
Python, Pandas, NumPy, Scikit-Learn, Matplotlib

### 📈 Feature Importance (Top 5)
1. Sex_male
2. Title_Mr
3. Pclass
4. Fare
5. Age

### 🔗 Dataset
[Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

### 👨‍💻 Author
Raviteja | Aspiring ML Engineer | Day 29 of 50 Days ML Challenge
