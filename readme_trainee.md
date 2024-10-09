# **NTT Stock Price Prediction Model**

#### **Project Overview**

This project aims to explore and compare multiple machine learning models for predicting stock prices, particularly focusing on the Japanese stock market. The models tested include ARIMA, LSTM, GRU, and XGBoost, each chosen for its unique capabilities in handling time-series data. This study provides insights into the predictive performance of these models, evaluating their strengths and limitations in real-world financial applications.

#### Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Prerequisites

What you need to install the software and how to install them:

* Python 3.8 or higher
* Jupyter Notebook or JupyterLab
* Required Python packages:

```
pip install numpy pandas matplotlib seaborn scikit-learn xgboost keras tensorflow statsmodels

```

#### Installation

1. **Clone the repository:**

   ```
   git clone https://github.com/pointarcher02/DeepcraftTrainee.git

   ```

#### Running the Notebook

```
jupyter notebook
```

Open the `Deepcraft Assignment_Trainee_Shashank Asthana.ipynb` notebook and run the cells sequentially to replicate the analysis.


#### File Descriptions

* `Deepcraft Assignment_Trainee_Shashank Asthana.ipynb`: Jupyter Notebook containing the data analysis and model development.


#### Models Used

* **ARIMA** : Autoregressive Integrated Moving Average model for baseline predictions.
* **LSTM** : Long Short-Term Memory networks to capture long-term dependencies in stock price movements.
* **GRU** : Gated Recurrent Unit networks offering a simpler alternative to LSTMs with similar performance benefits.
* **XGBoost** : eXtreme Gradient Boosting for robust, ensemble-based predictions.

#### Results

The project evaluates each model's performance using the Root Mean Squared Error (RMSE) metric. XGBoost outperformed other models with the lowest RMSE, demonstrating its effectiveness in predicting stock prices with high accuracy.


## Author

* **Shashank Shekhar Asthana**- [GitHubProfile](https://github.com/pointarcher02)
