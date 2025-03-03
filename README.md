# Bitcoin Price Prediction using LSTM  

This project uses a **Long Short-Term Memory (LSTM) Recurrent Neural Network (RNN)** to predict Bitcoin prices based on historical time series data.  

## Overview  
1. **Data Preprocessing**  
   - The dataset is loaded and filtered to include only relevant Bitcoin price data.  
   - The `datetime_id` column is converted to a proper date format.  
   - The data is normalized using **MinMaxScaler** to improve model performance.  

2. **Creating Time Series Sequences**  
   - A function is implemented to transform the dataset into sequences of input features (`look_back` period) and corresponding target labels.  

3. **Building the LSTM Model**  
   - A sequential **LSTM model** is defined with layers optimized for time series forecasting.  
   - The model is compiled with an appropriate loss function and optimizer.  

4. **Training and Evaluating the Model**  
   - The model is trained on historical data and validated using a test dataset.  
   - Predictions are generated and compared against actual values.  
   - The error is measured using **Root Mean Square Error (RMSE)**.  

5. **Visualization of Results**  
   - The predicted vs. actual Bitcoin prices are plotted for better analysis.  
   - The model’s ability to capture price trends is assessed.  

This project demonstrates how deep learning techniques can be leveraged for financial time series forecasting. 🚀
