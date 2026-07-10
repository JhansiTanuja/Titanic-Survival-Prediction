# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

The **Titanic Survival Prediction** project is a Machine Learning classification model developed using Python and Scikit-learn. The goal of this project is to predict whether a passenger survived the Titanic disaster based on various features such as age, gender, passenger class, fare, and family information.

This project follows the complete Machine Learning pipeline, including data preprocessing, feature engineering, model training, prediction, evaluation, and visualization.

---

## 🎯 Objective

The objective of this project is to build an accurate Machine Learning model that predicts passenger survival using historical Titanic passenger data.

---

## 📂 Dataset

The dataset contains passenger information, including:

- PassengerId
- Survived (Target Variable)
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

**Target Variable:**
- **0** → Did Not Survive
- **1** → Survived

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Visual Studio Code

---

## 📚 Machine Learning Workflow

The project follows these steps:

1. Import required libraries
2. Load the Titanic dataset
3. Explore the dataset
4. Handle missing values
5. Encode categorical variables
6. Select features and target variable
7. Split the dataset into training and testing sets
8. Train the Random Forest Classifier
9. Predict passenger survival
10. Evaluate model performance
11. Visualize the results

---

## 🤖 Machine Learning Algorithm

### Random Forest Classifier

Random Forest is an ensemble Machine Learning algorithm that builds multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.

---

## 📊 Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values
- Filling missing Age values with the median
- Filling missing Embarked values with the mode
- Replacing missing Cabin values with "Unknown"
- Label Encoding for categorical columns
- Removing unnecessary columns such as PassengerId, Name, Ticket, and Cabin

---

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Visualization

---

## 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── titanic_survival_prediction.py
├── Titanic-Dataset.csv
├── README.md
└── screenshots/
    ├── output.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/YourUsername/Titanic-Survival-Prediction.git
```

Move into the project folder:

```bash
cd Titanic-Survival-Prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## ▶️ Run the Project

Run the following command:

```bash
python titanic_survival_prediction.py
```

---

## 📸 Expected Output

After running the project, you will see:

- Dataset Information
- Missing Value Analysis
- Accuracy Score
- Classification Report
- Confusion Matrix
- Feature Importance Graph
- Sample Prediction Results

---

## 📊 Sample Workflow

- Load Dataset
- Clean Data
- Encode Features
- Train Model
- Test Model
- Evaluate Accuracy
- Visualize Results

---

## 🚀 Skills Gained

This project helped improve my knowledge in:

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning Classification
- Random Forest Algorithm
- Data Visualization
- Model Evaluation
- Python Programming

---

## 🔮 Future Enhancements

- Hyperparameter tuning for better accuracy
- Compare different classification algorithms
- Deploy the model using Streamlit or Flask
- Build an interactive web application
- Add cross-validation for more reliable evaluation

---

## 📷 Output Screenshots

You can add screenshots of:

- Dataset Preview
- Confusion Matrix
- Feature Importance Chart
- Prediction Results
- Accuracy Output

Create a folder named **screenshots** and save the images there.

---

## 🤝 Contributing

Contributions are welcome!

If you have suggestions for improving this project, feel free to fork the repository and submit a pull request.

---

## 👩‍💻 Author

# **Jhansi Tanuja**

**Computer Science Student | Aspiring Data Scientist | Machine Learning Enthusiast**

- 🌱 Currently learning Data Science and Machine Learning
- 💻 Passionate about Python, AI, and Data Analytics
- 🚀 Building real-world projects to enhance my technical skills

---

## ⭐ Acknowledgements

- Kaggle Titanic Dataset
- Scikit-learn Documentation
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

## 📜 License

This project is created for educational and learning purposes.

---

### ⭐ If you found this project helpful, consider giving it a star on GitHub!
