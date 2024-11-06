# Stock Price Prediction using Perceptron Learning Rule

## Overview
This project demonstrates the use of the **Perceptron Learning Rule** to predict future stock price trends based on historical data. Using daily stock data from **Honda Motor Co., Ltd.**, the model aims to classify the closing price movement for the next day.

## Dataset
The dataset consists of daily stock market features, including:
- Opening, High, Low, Closing, and Adjusted Closing prices
- Trading Volume

The **target variable** is `Next_Close`, which indicates if the next day’s closing price will be higher (1) or lower (0) than today’s.

## Project Structure
1. **Data Loading and Preprocessing**  
   - Load and clean the dataset
   - Exploratory Data Analysis (EDA) to assess feature distributions
   - Feature engineering for the `Next_Close` target variable

2. **Exploratory Data Analysis (EDA)**
   - Analyzed stock price distribution and trading volume variability
   - Key insights on price stability and volume trends

3. **Feature Selection and Standardization**
   - Selected key price features for prediction (`Open`, `High`, `Low`, `Close`, `Adj Close`)
   - Scaled features using standardization for improved model performance

4. **Model Implementation**
   - Trained a Perceptron model to classify the direction of stock price movement
   - Evaluated model performance using accuracy and confusion matrix

5. **Results**
   - The model achieved an accuracy of `60%` on test data, with insights into prediction errors via a confusion matrix.

## Conclusion
This project highlights the viability of the Perceptron Learning Rule for financial trend prediction. Future improvements include experimenting with advanced models and more feature engineering.

## Future Work
- Experiment with varying Perceptron parameters (learning rate, iterations) to enhance accuracy
- Consider ensemble methods or deep learning models for performance comparison
- Enhance feature engineering with technical indicators for stock trends

---

