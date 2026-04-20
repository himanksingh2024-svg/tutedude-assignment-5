# Titanic Survival Prediction (Naive Bayes)


This project uses the Naive Bayes algorithm to predict whether a passenger survived the Titanic disaster.

## 📂 Dataset
The dataset is taken from Kaggle: *Titanic - Machine Learning from Disaster*.

## ⚙️ Steps Performed
- Data loading and exploration
- Handling missing values (Age, Embarked, Cabin)
- Encoding categorical variables (Sex, Embarked)
- Feature selection
- Train-test split
- Model training using Gaussian Naive Bayes
- Model evaluation using accuracy, confusion matrix, and classification report

## 📊 Results
The model achieved approximately **81% accuracy**.

## 📈 Key Insights
- Gender is a strong predictor of survival
- Passenger class and fare also influence survival chances
- Some misclassifications still occur due to model limitations

## 🚀 Conclusion
Naive Bayes provides a simple and fast approach for classification, but its assumption of feature independence limits performance. More advanced models could improve accuracy further.
