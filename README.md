# Estimation of Obesity Levels Based on Eating Habits and Physical Condition

This project aims to predict obesity levels based on individuals' eating habits and physical conditions using machine learning techniques. The dataset used contains health-related and behavioral information from individuals in Mexico, Peru, and Colombia. The project was developed as part of the HubbleMind Data Science Program.

## 📊 Problem Statement

Obesity has become a critical public health issue across the globe. By leveraging data on individual habits and conditions, this project seeks to:
- Classify obesity levels.
- Identify the most important features contributing to obesity.
- Provide insights that could support preventive healthcare decisions.

## 📁 Dataset

The dataset is publicly available and includes the following types of features:
- Demographic: Gender, Age, Country
- Physical Condition: Height, Weight, BMI
- Behavioral: Frequency of meals, consumption of high-calorie food, physical activity, water intake, etc.

### Dataset Columns Include:
- `Gender`, `Age`, `Height`, `Weight`
- Eating habits: `FCVC` (Frequency of vegetable consumption), `NCP` (Number of main meals), `CAEC` (Consumption of food between meals), `CH2O` (Water consumption)
- Physical activity: `FAF` (Frequency of physical activity)
- Lifestyle and health conditions: `SMOKE`, `SCC` (Calories monitoring), `CALC` (Alcohol consumption), `MTRANS` (Transportation)
- Target: `NObesity` (Obesity level category)

## 🧠 Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn** for data exploration and visualization
- **Scikit-learn** for preprocessing, modeling, and evaluation

## 📈 Machine Learning Workflow

1. **Data Cleaning**: Handle missing values and outliers.
2. **Exploratory Data Analysis (EDA)**: Understand distributions, feature relationships, and correlations.
3. **Feature Engineering**: Encoding categorical variables, scaling.
4. **Model Training**: Multiple algorithms tested including Logistic Regression, Decision Tree, Random Forest, and more.
5. **Evaluation**: Accuracy, precision, recall, F1-score, and confusion matrix used to evaluate performance.

## 🔍 Results

- The best-performing model was able to classify obesity levels with high accuracy.
- The most important predictive features included frequency of physical activity, water intake, and consumption of food between meals.

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/obesity-prediction.git
   cd obesity-prediction
