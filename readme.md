# Time Series Classification | LSTM, CNN, Transformer, TCN, Serial, Parallel Model Collection

Preface  
This article introduces an innovative classification model based on the Fast Fourier Transform (FFT), Time-frequency feature fusion, FFT-CNN-BiGRU-Attention for a time series classification task dataset.
1. Model Introduction and Innovation Points  
1.1 Model Introduction  
● Data Set: Time series classification task dataset  
● Environment Framework: Python 3.9 PyTorch 2.1 or higher versions are compatible  
● User Group: Beginners learning, paper requirements  
● Code Guarantee: Code comments are detailed, ready to run without modification.  
● Supporting Files: Comprehensive tutorials on environment setup, model, parameter explanation documents  
Including complete process data code processing:  
Dataset creation, data loading, model definition, parameter setting, model training, model testing, prediction visualization, model evaluation  
1.2 Innovation Points Introduction  
 (1)Fast Fourier Transform (FFT):  
FFT is a fast algorithm for computing the Discrete Fourier Transform (DFT), which converts time domain signals into the frequency domain. This is very useful in time series analysis as the frequency domain features can reveal patterns that are not apparent in the time domain. In the innovative model, FFT is used to extract the frequency domain features of the time series, which when combined with the original time domain features, can improve the classification performance of the model.  
 (2)Convolutional Neural Network (CNN):  
In the innovative model, CNN is used to extract local patterns and features from the frequency domain features after FFT processing, as well as the original time series data. These features could be short-term changes or some kind of local consistency.  
 (3)Bidirectional Gated Recurrent Unit (BiGRU):  
\t
1. GRU is a variant of Recurrent Neural Networks (RNN) capable of effectively capturing long-term dependencies in sequence data. The BiGRU enhances context understanding by processing data from both forward and backward directions.
2. Attention Mechanism:
   - Attention mechanisms are used to identify the most relevant parts of the input sequences, enabling the model to focus on useful features. This mechanism is particularly useful for handling long sequence data, helping the model extract key features amidst a vast amount of information.
   - In this model, the attention mechanism assists BiGRU in focusing on time steps or features that have the greatest impact on the classification task, thereby enhancing the overall performance and interpretability of the model.
3. FFT-CNN-BiGRU-Attention models can effectively extract and utilize both temporal and frequency domain features of time series data through deep learning methods for efficient classification tasks. This combination leverages the strengths of each module, making the model more robust and accurate when dealing with complex time series data.
4. Data Preprocessing:
   - The dataset is formatted as a CSV file, with each row representing a time series sample and the last column corresponding to the label value, which can be flexibly replaced with the dataset!
   - The training set, validation set, and test set are divided as 7:2:1:
5. Classification Model Based on FFT-CNN-BiGRU-Attention:
   - 5.1 Define the FFT-CNN-BiGRU-Attention network model
   - 5.2 Set parameters and train the model
50 epochs, accuracy 100%, FFT-CNN-BiGRU-Attention significantly improves network classification performance. The model effectively extracts multi-scale features from time series data, with fast convergence and exceptionally superior performance.
4 Model Evaluation and Visualization
4.1 Model Evaluation
4.2 Classification Visualization
(1) Confusion Matrix
(2) Classification Label Visualization
(3) Original Data t-SNE Feature Visualization
Model Training Post-t-SNE Feature Visualization:
Click to download: Complete original data, Python code
Previously excellent content:
Time Series Forecasting: Analysis and comparison of LSTM, ARIMA, Holt-Winters, SARIMA models
Wind Speed Forecast (I): Introduction and preprocessing of the dataset
Wind Speed Forecast (II): EMD-LSTM model based on Pytorch
Wind Speed Forecast (III): EMD-LSTM-Attention model
Wind Speed Forecast (IV): EMD-Transformer model based on Pytorch
Wind Speed Forecast (V): EMD-CNN-LSTM model based on Pytorch
Wind Speed Forecast (VI): EMD-CNN-GRU parallel model based on Pytorch
CEEMDAN + combined forecasting models (BiLSTM-Attention + ARIMA)
CEEMDAN + combined forecasting models (CNN-LSTM + ARIMA)
CEEMDAN + combined forecasting models (Transformer - BiLSTM + ARIMA)
CEEMDAN + combined forecasting models (CNN-Transformer + ARIMA)
Multi-feature Variable Sequence Prediction (I) - CNN-LSTM Wind Speed Prediction Model
Multi-feature Variable Sequence Prediction (II) - CNN-LSTM-Attention Wind Speed Prediction Model
Multi-feature Variable Sequence Prediction (III) - CNN-Transformer Wind Speed Prediction Model
Multi-feature Variable Sequence Prediction (IV) Transformer-BiLSTM Wind Speed Prediction Model
Multi-feature Variable Sequence Prediction (V) CEEMDAN+CNN-LSTM Wind Speed Prediction Model
Multi-feature Variable Sequence Prediction (VI) CEEMDAN+CNN-Transformer Wind Speed Prediction Model
Prediction Model Based on the Particle Swarm Optimization Algorithm SSA - CEEMDAN-BiLSTM-Attention
Prediction Model Based on the Particle Swarm Optimization Algorithm SSA - CEEMDAN-Transformer-BiGRU
Superior Prediction Model: Secondary Decomposition-Combination Prediction
Multi-feature Variable Sequence Prediction (VII) CEEMDAN+Transformer-BiLSTM Prediction Model
Multi-feature Variable Sequence Prediction (VIII) Prediction Model Based on the Particle Swarm Optimization Algorithm for CEEMDAN-SSA-BiLSTM
Multi-feature Variable Sequence Prediction (11) Prediction Model Based on Pytorch's TCN-GRU
VMD + CEEMDAN Secondary Decomposition, CNN-LSTM Prediction Model
VMD + CEEMDAN Secondary Decomposition, CNN-Transformer Prediction Model
VMD + CEEMDAN Secondary Decomposition, Transformer-BiGRU Prediction Model
Prediction Model Based on the Particle Swarm Optimization Algorithm SSA - Code Family Kit
Introduction to Electric Power Transformer Data Set and Preprocessing
SCI 1 Region High Innovative Prediction Model!

## Images

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
