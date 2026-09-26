# AI-Based Water Allocation and Shortage Prediction System

## Project Description

This project is a web-based system that uses Machine Learning to predict water demand and identify possible water shortages in different areas.

## Features

- Water demand prediction
- Water shortage detection
- Area-wise analysis
- Rainfall and temperature analysis
- AI-based water allocation
- Interactive dashboard
- 30-day water trend visualization

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Pandas
- Scikit-learn
- Random Forest

## Machine Learning

A Random Forest model is used to predict water demand based on:

- Population
- Rainfall
- Temperature
- Available Water

The predicted demand is compared with available water to identify the shortage level.

## Project Flow

Dataset
→ Random Forest
→ Predicted Water Demand
→ Shortage Calculation
→ Water Allocation
→ Dashboard

## How to Run

```bash
pip install -r requirements.txt
python app.py
