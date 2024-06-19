# Sales Prediction

This project predicts advertising cost based on sales using simple linear regression.

## Files
- `requirements.txt`: install tools
- `regression_endpoint.py`: Flask API to serve predictions.
- `regression.pkl`: The trained model.

## Requirements
- Flask==2.2.3
- Werkzeug
- numpy
- pandas==1.5.3
- scikit-learn==1.2.1
- pandas
- setuptools


## Usage
1. Run `regression_endpoint.py` to train the model and save it to `regression.pkl`.
2. Start the Flask server by running `regression_endpoint.py`.
3. Make predictions by sending requests to the `/predict-advertising` endpoint with the `sales` parameter.
