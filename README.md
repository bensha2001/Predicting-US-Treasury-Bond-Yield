# Predicting US Treasury Bond Yields

## Overview
This project explores the application of classical and quantum machine learning techniques for forecasting the U.S. 10-year Treasury bond yields using macroeconomic indicators.

## Features
- Implementation of traditional ensemble methods (XGBoost and AdaBoost)
- Sequential neural architectures including LSTM and Hybrid Quantum LSTM (QLSTM) model using PennyLane and TensorFlow
- Comprehensive feature analysis using permutation-based importance
- Performance evaluation during market stress periods (e.g., COVID-19)

## Technical Stack
- Python
- TensorFlow
- PennyLane (for quantum computing)
- XGBoost
- AdaBoost

## Input Features
The model utilizes various macroeconomic indicators including:
- Fed Funds Rate
- Consumer Sentiment Index
- Crude Oil Futures
- Additional economic variables

## Key Findings
- LSTM models demonstrated superior performance in capturing both short and long-term dependencies
- Enhanced accuracy during market stress periods
- QLSTM showed promising results as a proof-of-concept for quantum-enhanced finance
- Identification of key influential features through permutation analysis


## Project Structure
The project is organized into several Jupyter notebooks, each focusing on specific aspects of the analysis and modeling:

### Data Analysis
- `PrecovidDataEDA.ipynb`: Comprehensive data analysis excluding post-COVID data with correlation heatmap visualization
- `EDA(includingpost2020).ipynb`: Exploratory data analysis including post-COVID data

### Classical Machine Learning Models
- `AdaBoostModelFinal.ipynb`: Implementation of AdaBoost model with hyperparameter optimization
- `Adaboost_Permutation_Importance.ipynb`: Feature importance analysis for the AdaBoost model
- `XGBoostModelFinal.ipynb`: Implementation of XGBoost model with hyperparameter optimization
- `XGBoost_permutation_importance.ipynb`: Feature importance analysis for the XGBoost model

### Deep Learning Models
- `LSTMFINAL.ipynb`: Implementation of LSTM model for yield prediction
- `QLSTMFINAL.ipynb`: Implementation of quantum-enhanced LSTM model for yield prediction

## Contact
For questions, suggestions, or collaboration opportunities, please reach out to:

- **Email:** [fathimabensha2001@gmail.com](mailto:fathimabensha2001@gmail.com)
- **LinkedIn:** [Fathima Bensha](https://www.linkedin.com/in/fathima-bensha-b12743230)

