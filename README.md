# US Store Product Price Prediction

This project focuses on predicting product prices in US stores using various statistical and deep learning techniques, including **SARIMAX**, **ARIMAX**, and **Deep Learning** models. The objective is to develop accurate price prediction models and explore advanced techniques to enhance their performance.

---

## Features and Highlights

- **Statistical Models**:
  - **SARIMAX**: Seasonal Autoregressive Integrated Moving Average with Exogenous variables for capturing seasonality and external factors.
  - **ARIMAX**: Autoregressive Integrated Moving Average with Exogenous variables for modeling linear relationships.
  
- **Deep Learning Models**:
  - Utilized deep neural networks for feature extraction and price prediction.
  - Incorporated techniques such as dropout, batch normalization, and learning rate scheduling to optimize performance.

- **Performance Optimization**:
  - Fine-tuned hyperparameters using grid search and Bayesian optimization.
  - Performed feature engineering to improve model inputs.
  - Evaluated models using metrics like MAE, RMSE, and MAPE.

---

## Project Workflow

1. **Data Preprocessing**:
   - Cleaned and preprocessed the dataset by handling missing values and outliers.
   - Conducted feature engineering, including time-series transformations, one-hot encoding, and scaling.

2. **Exploratory Data Analysis**:
   - Analyzed seasonal trends, cyclic patterns, and correlations in data.
   - Visualized price fluctuations over time.

3. **Model Development**:
   - Built SARIMAX and ARIMAX models for statistical predictions.
   - Developed deep learning models using frameworks like TensorFlow and Keras.

4. **Performance Tuning**:
   - Enhanced statistical models using parameter tuning.
   - Improved deep learning models with advanced techniques and regularization.

5. **Model Evaluation**:
   - Compared statistical and deep learning approaches.
   - Assessed the impact of optimization techniques on performance.

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/whoisusmanali/US-Stores-Sales-Data.git
   cd US-Stores-Sales-Data
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the data preprocessing script:
   ```bash
   python preprocess.py
   ```

4. Train the models:
   ```bash
   python train.py --model SARIMAX
   python train.py --model ARIMAX
   python train.py --model DeepLearning
   ```

5. Evaluate the models:
   ```bash
   python evaluate.py
   ```

---

## Results

- **SARIMAX**: Captured seasonal variations effectively, achieving moderate accuracy.
- **ARIMAX**: Performed well in modeling linear trends and relationships with external factors.
- **Deep Learning**: Provided the most accurate predictions, leveraging non-linear patterns in data.
---

## Future Improvements

- Experiment with hybrid models combining statistical and deep learning techniques.
- Incorporate additional features such as economic indicators and weather data.
- Explore transfer learning for improving deep learning model performance.