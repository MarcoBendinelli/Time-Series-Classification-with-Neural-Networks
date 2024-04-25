# Neural Networks for Time Series Classification :watch:

This project explores deep learning techniques to classify samples in multivariate time series format. By leveraging advanced Neural Networks, the most accurate models for this task are identified.

The objective is to accurately map the information contained in features calculated over time to their labels.

Various techniques are explored, including:
- Data preprocessing with z-score and MinMaxScaler
- Residual Neural Networks
- Activation functions like ReLU, LSTM

[Full Report](Report.pdf)

## Performance

The dataset is split into 80% for training and 20% for validation. The model, trained with Early Stopping (patience 50 epochs) based on validation accuracy, reached peak performance at epoch 156 with the following indexes:
- Train. loss: 0.0511, Train. acc.: 99.28%
- Val. loss: 1.0963, Val. acc.: 73.87%
