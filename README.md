## Potato Disease Classification

Project Overview ->(document)[localhost:8000/predict]
This project focuses on leveraging Convolutional Neural Networks (CNNs) for the accurate classification of potato diseases. The implementation incorporates FastAPI for creating API endpoints and Postman for streamlined testing during the development process.

## Tools Used

1. FastAPI: Implemented to create API endpoints for serving the potato disease classification model.
2. Postman: Utilized for testing API endpoints and ensuring robust functionality.
3. CNN (Convolutional Neural Network): Applied for training and classifying potato diseases based on image data.

Model Performance
CNN Model: The core machine learning model responsible for accurately classifying potato diseases.
FastAPI Implementation: Codebase for the FastAPI application, facilitating model exposure through API endpoints.
Postman Collection: A comprehensive set of API tests for ensuring robust functionality.
Running the Project
To run the project seamlessly, follow these steps:

### Install Dependencies:

pip install -r requirements.txt

### Run FastAPI Application:

uvicorn api.main:app --reload

### Testing with Postman:
Utilize the provided Postman collection to test API endpoints and validate the model's performance.