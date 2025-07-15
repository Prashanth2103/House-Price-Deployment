# House Price Prediction – End-to-End ML Deployment

## Objective
Build, deploy, and serve a house price prediction model using Flask API.

## 🛠Stack Used
- Python, Pandas, Scikit-learn
- Flask (API deployment)
- Docker (containerisation)
- AWS EC2 (cloud hosting)
- HTML + Bootstrap (frontend UI)

## Flow
1. Model training and pickle export
2. Flask API serving prediction endpoint
3. Dockerfile for containerisation
4. EC2 deployment guide
5. Sample UI integration

## API Demo
POST `/predict` with JSON:  
```json
{"bedrooms": 3, "sqft": 1450, "location": "London"}
