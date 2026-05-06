# California Housing Price Prediction 🏠

This project aims to predict house prices in California using various Machine Learning algorithms. The dataset used is the classic **California Housing dataset**, and the project explores the transition from a simple Linear Regression model to a more robust Random Forest Regressor.

## 🚀 Project Overview
In this project, I performed end-to-end machine learning tasks including:
*   Data Loading and Exploratory Data Analysis (EDA).
*   Feature Scaling using `StandardScaler`.
*   Model selection (Linear Regression vs. Random Forest).
*   Hyperparameter tuning to improve accuracy.
*   Model evaluation and saving the final model for production.

## 📊 Performance Summary
*   **Linear Regression:** Achieved an R-Squared score of **~57%**.
*   **Random Forest Regressor:** Significantly improved the accuracy to **~80.5%**.
*   **Mean Squared Error (MSE):** Reduced from 0.55 to **0.25**.

## 🛠️ Technologies Used
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Joblib
*   **Tools:** Jupyter Notebook / Google Colab

## 📁 Directory Structure
*   `RealDatasetHousePricePredict.ipynb`: The main notebook containing all the code and visualizations.
*   `housing_scaler.pkl`: The saved scaler object to process new input data.
*   `requirements.txt`: List of dependencies required to run the project.
*   *(Note: The final model file is stored locally due to size constraints).*

## 📈 Key Insights
*   **Median Income (MedInc):** Identified as the most significant factor affecting house prices.
*   **Scalability:** Demonstrated how ensemble methods like Random Forest handle non-linear data better than simple linear models.

## 👨‍💻 Author
**Md. Anwar Hossen**
Computer Science and Engineering Student
Presidency University, Bangladesh

---
*This project is part of my professional portfolio in Machine Learning and Data Science.*
