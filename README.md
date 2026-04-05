# PHM-AI(reg no:29,36)
A hybrid AI framework integrating image-based CNN detection and time-series LSTM prediction for proactive food spoilage monitoring and risk control.

## Project Workflow

- Collected and preprocessed food image dataset (resizing, normalization)
- Trained a CNN model to classify images as fresh or spoiled
- Generated sensor dataset (temperature, humidity, gas)
- Calculated spoilage score from sensor values
- Converted sensor data into time-series sequences
- Trained an LSTM model to predict spoilage trends
- Combined CNN and LSTM outputs using weighted fusion
- Classified final output into Low, Medium, or High risk
