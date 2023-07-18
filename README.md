# Flight Passenger Prediction using SARIMAX Model

This project aims to predict the future amount of flight passengers using the SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) model. The data used for this project is sourced from [Kaggle.com](https://www.kaggle.com/).

## Dataset

The dataset used for this project can be obtained from Kaggle.com. It consists of historical flight passenger data, including the number of passengers and corresponding dates. The dataset is preprocessed to convert the passenger counts into log values for better modeling. You can download the dataset from the following link: [Flight Passenger Dataset](https://www.kaggle.com/datasets/rakannimer/air-passengers).

## Code Overview

- `passengers_forecast.ipynb`: Jupyter Notebook containing the code for data preprocessing, SARIMAX modeling, and evaluation of the predictions.

## Running the Code

1. Download the Flight Passenger Dataset from Kaggle.com and place it in the same directory as the Jupyter Notebook.
2. Open `passengers_forecast.ipynb` in Google Colab.
3. Run the code cells sequentially to preprocess the data, train the SARIMAX model, and generate predictions for future flight passenger counts.
4. The predicted values will be visualized alongside the actual passenger counts using line plots.

## Results

The SARIMAX model will provide predictions for the future amount of flight passengers based on historical data. The predicted values will be evaluated using metrics such as RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R2 Score. These metrics will give insights into the accuracy and performance of the model.

## Conclusion

In this project, we used the SARIMAX model to predict the future amount of flight passengers. By leveraging historical data and considering seasonal patterns, the model provides valuable insights into passenger trends. The predictions can be useful for airlines and travel industry professionals to plan and optimize their operations accordingly.

Please refer to the Jupyter Notebook for detailed code implementation and further exploration of the results.

## Acknowledgments

- Molly Liebeskind for the [Sales Forecasting](https://github.com/mollyliebeskind/sales_forecasting) repository, which served as the basis for this project.
- Kaggle.com for providing the Flight Passenger Dataset.
