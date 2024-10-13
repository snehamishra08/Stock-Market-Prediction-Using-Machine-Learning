# Stock-Market-Prediction-Using-Machine-Learning
This project uses various machine learning models to predict stock market metrics such as Open, High, Low, Close, and RSI (Relative Strength Index). The models are trained using historical stock data, and predictions are made based on selected features.
Features:
    1.User-Driven Prediction: The code allows users to select which metric (Open, High, Low, Close, or RSI) they want to predict.
    2.Multiple Machine Learning Algorithms: Includes implementations of popular algorithms such as:
        K-Nearest Neighbors (KNN)
        Random Forest Regressor
        Support Vector Regressor (SVR)
        Logistic Regression
        Linear Regression
    3.Performance Evaluation:
        The models are evaluated using:
            R² Score: Measures the accuracy of the models.
            Root Mean Squared Error (RMSE): Measures the prediction error.
        Cross-validation is also used to ensure robust model performance with K-Fold cross-validation.
    4.Data Normalization: The code includes StandardScaler for models requiring feature scaling (e.g., SVR).
    5.Visualization: Compares the accuracy and performance of each model through visual plots.

    
Dataset:
The dataset includes historical stock data for Maruti Suzuki, with metrics like Open, High, Low, Close, Adjusted Close, Volume, and technical indicators like RSI and SMA (Simple Moving Average).

How It Works:
    The user selects the target variable to predict and the time interval.
    The dataset is split into training and testing sets.
    Multiple models are trained, and their performance is compared.
    The code also makes predictions on future stock data using the best-performing model.
Requirements:
    Python 3.x
    Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
