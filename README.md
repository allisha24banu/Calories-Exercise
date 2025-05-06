# Calories & Exercise Analysis 🏋️‍♀️🔥

This project explores the relationship between exercise data and calories burned using data analysis and machine learning models. It includes insights drawn from demographic, biometric, and exercise-related variables to predict calories burned during physical activities.

## 🔗 Dataset Links

- 📊 [Exercise Data CSV](https://github.com/allisha24banu/Calories-Exercise/blob/main/exercise.csv)
- 🔥 [Calories Data CSV](https://github.com/allisha24banu/Calories-Exercise/blob/main/calories.csv)
- 📒 [Jupyter Notebook](https://github.com/allisha24banu/Calories-Exercise/blob/main/Calories%20%26%20Exercise.ipynb)

## 📁 Project Structure

- `Calories & Exercise.ipynb`: Main notebook containing data analysis, preprocessing, visualization, and machine learning models.
- `exercise.csv`: Contains user details like gender, age, height, weight, exercise duration, heart rate, and body temperature.
- `calories.csv`: Contains calories burned by corresponding users.
- `README.md`: Project summary and insights (this file).

## 📌 Key Objectives

- Understand how physical attributes and exercise metrics influence calories burned.
- Build and compare regression models to predict calories burned.
- Visualize patterns in physical data using charts and plots.

## 🧠 Insights from the Data

1. **Correlation Observed**:
   - Exercise duration and heart rate are positively correlated with calories burned.
   - Body temperature tends to rise with increased workout intensity.

2. **Demographics**:
   - Both male and female participants are included across varied age ranges.
   - Calorie burn patterns slightly differ across gender and age groups.

3. **Missing & Duplicate Data**:
   - No missing values were found.
   - No duplicate rows were detected.

4. **Visualizations**:
   - Histograms and countplots show distribution of each variable.
   - Helps understand skewness, modality, and general trends.

5. **Modeling**:
   - Applied models: Linear Regression, Random Forest Regressor, XGBoost Regressor.
   - **XGBoost** performed best in predicting calories burned with the highest R² score and lowest error margin.

## 📈 Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook
