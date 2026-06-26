# ML API Docker Demo

## Project Summary

This project demonstrates how to build, containerize, and run a Machine Learning API using **FastAPI**, **Docker**, and **GitHub Codespaces**. A **Random Forest model** is trained on the **Iris dataset**, saved using **joblib**, and exposed through API endpoints for training, testing, and prediction.

## Technologies Used

* **FastAPI** → Create REST API endpoints
* **Uvicorn** → Run FastAPI server
* **scikit-learn** → Train ML model
* **joblib** → Save and load trained model
* **Docker** → Containerize application
* **GitHub Codespaces** → Cloud development environment
* **Swagger UI** → Test APIs in browser

## Implemented Features

* Created FastAPI application
* Added API endpoints:

  * `GET /` → Home endpoint
  * `POST /train` → Train model
  * `GET /test` → Test model accuracy
  * `POST /predict` → Predict flower type
* Trained a Random Forest classifier on Iris dataset
* Saved trained model as `iris_model.pkl`
* Containerized the application using Docker
* Ran and tested the API using Swagger UI

## Workflow

```text
Browser
   ↓
Docker Container
   ↓
Uvicorn
   ↓
FastAPI
   ↓
ML Model
   ↓
Prediction Response
```

## Output

* Successfully trained and tested the ML model
* Generated prediction results through API calls
* Deployed and accessed the application via Docker container and Swagger UI
