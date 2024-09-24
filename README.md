# SP500_Predictors_LSTM_Linear_Regression

## Overview

This project utilizes Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data. The goal is to explore the capabilities of deep learning in time series forecasting, specifically in the financial domain, using Python and popular libraries such as TensorFlow and Keras. The project also compares LSTM predictions with a traditional Linear Regression model to evaluate performance differences.

## Table of Contents

- Features
- Technologies Used
- Data
- Results
- Contributing
- License

## Features

- Data preprocessing and normalization using `MinMaxScaler`.
- Implementation of LSTM for time series forecasting.
- Hyperparameter tuning with Keras Tuner to optimize the LSTM model.
- Comparison of LSTM performance against a Linear Regression model.
- Calculation and reporting of Mean Squared Error (MSE) for performance evaluation of both models.
- Visualization of predictions against actual stock prices.

## Technologies Used

- **Python**: Programming language used for the project.
- **TensorFlow**: Deep learning framework used for building and training the LSTM model.
- **Keras**: High-level API for building and training deep learning models.
- **NumPy**: Library for numerical operations.
- **Pandas**: Data manipulation and analysis library.
- **Scikit-learn**: Machine learning library for model evaluation, including Linear Regression.
- **Matplotlib**: Library for data visualization.


## Data

The dataset used in this project should be structured with a date column and a price column (e.g., "Close" prices). You can replace the provided dataset with your own historical stock prices.

## Results

The performance of the models is evaluated using Mean Squared Error (MSE). The results will be printed in the console upon running the main script, comparing the predictions of the LSTM model against the Linear Regression model. Visualization will also help in understanding the model performance.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This revision explicitly mentions the Linear Regression model in multiple sections, emphasizing its role in the project. Let me know if you need any further adjustments or additions!
