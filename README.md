# Rice Leaf Disease Prediction API

This is a FastAPI server designed to diagnose diseases in rice leaves using a machine learning model. It accepts images of rice leaves through an API endpoint and returns predictions along with confidence levels.

## Features

- **Health Check Endpoint**: A simple GET request to check if the API is running.
- **Disease Prediction**: Accepts image uploads and returns the type of disease and the confidence level of the prediction.

## How to Run Locally

### Prerequisites

- Python 3.6+
- FastAPI
- Uvicorn
- TensorFlow
- NumPy
- Pillow
