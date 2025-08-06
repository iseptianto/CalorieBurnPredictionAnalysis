# alorieBurnPredictionAnalysis with Machine Learning

[](https://opensource.org/licenses/MIT)
[](https://www.python.org/downloads/)
[](https://scikit-learn.org/)

A machine learning project to predict the number of calories burned during physical activity based on an individual's physiological attributes and exercise data.

-----

## 📝 Description

This project aims to build and evaluate a machine learning model capable of providing an accurate estimation of calories burned. The model is trained on a dataset containing information such as age, gender, weight, exercise duration, heart rate, and body temperature. This project covers the entire machine learning workflow, from exploratory data analysis, preprocessing, and model training, to performance evaluation.

## 🎯 Problem Background

Understanding the number of calories burned is a crucial component of weight management, fitness programs, and general health monitoring. However, manual calculation can be impractical and inaccurate. By leveraging machine learning, we can create a predictive model that provides personalized and reliable estimates, helping users stay motivated and achieve their fitness goals.

## ✨ Key Features

  - **Calorie Prediction**: Provides an estimate of the number of calories burned based on user inputs.
  - **Exploratory Data Analysis (EDA)**: A Jupyter Notebook demonstrating data analysis and visualization to gain insights.
  - **Machine Learning Model**: Utilizes a powerful regression model like XGBoost for high accuracy.
  - **Model Evaluation**: The model's performance is measured using standard metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared ($R^2$).

## 📊 Dataset

The model is trained using a combined dataset that includes physiological and exercise data. The primary dataset used in this project can be found on Kaggle: [Calories Burnt Prediction Dataset](https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos).

The features used in the dataset include:

  - `User_ID`: A unique identifier for each user.
  - `Gender`: The user's gender ('male' or 'female').
  - `Age`: The user's age in years.
  - `Height`: The user's height in centimeters.
  - `Weight`: The user's weight in kilograms.
  - `Duration`: The duration of physical activity in minutes.
  - `Heart_Rate`: The average heart rate during the activity.
  - `Body_Temp`: The body temperature during the activity.
  - `Calories`: **(Target)** The number of calories burned.

## 🛠️ Tech Stack

  - **Programming Language**: Python 3.8+
  - **Data Analysis Libraries**: Pandas, NumPy
  - **Visualization Libraries**: Matplotlib, Seaborn
  - **Machine Learning Libraries**: Scikit-learn, XGBoost
  - **Environment**: Jupyter Notebook, Google Colab

## 🤖 Model and Evaluation

Several regression models were tested, and the **XGBoost Regressor** showed the best performance. This model was chosen for its ability to handle non-linear relationships in the data and its robustness against overfitting.

The model's performance was evaluated using the following metrics on the test data:

  - **Mean Absolute Error (MAE)**: The average absolute difference between the predicted and actual values.
  - **Mean Squared Error (MSE)**: The average of the squared differences.
  - **R-squared ($R^2$)**: The coefficient of determination, which measures how well the model explains the variance in the data.

The evaluation results show that the model achieves a very high $R^2$ score (e.g., \> 0.98), indicating a very strong correlation between the predicted and actual values.

## 🤝 Contributing

Contributions to the development of this project are very welcome\! If you have ideas for improvements or find a bug, please follow these steps:

1.  **Fork** this repository.
2.  Create a new **Branch** (`git checkout -b feature/NewFeature`).
3.  Make your changes and **Commit** them (`git commit -m 'Add NewFeature'`).
4.  **Push** to your Branch (`git push origin feature/NewFeature`).
5.  Create a new **Pull Request**.

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

-----
