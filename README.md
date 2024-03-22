# Loan-Risk-Mitigation

## Description
Automated underwriter modeling process, the long-term growth projection for loan risk mitigation.

Technologies: Python, NumPy, pandas, statsmodels, matplotlib,  scikit-learn, TensorFlow, Keras

## Process
-  Generate Python scripts to source financial corporate data
-  Use a RandomForestClassifier to perform effective feature importance
-  Develop and train ARIMA Models (Traditional, Seasonal, VAR) 
-  Develop and train a LSTM Model (RNN)

## Results
- 4 startups, 12,384 data points (70%) in training set, 3,097 data points (30%) in testing set
- Primary features: Current and Noncurrent Assets and Liabilities, Equity, Expenses, Sales, QR Assets
- Secondary Features: Current ratio, debt-to-equity ratio, acid test ratio, net profit margin, return on equity, debt-to-asset ratio, gross profit margin
- Test Set Mean Average Error: $1420.62
- ARIMA works well for individual datasets and short term, but difficult for comprehensive dataset and needs a lot of data
- LSTM performs very well on smaller spikes and decent on larger ones
