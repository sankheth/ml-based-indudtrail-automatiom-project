# AI Safety Monitoring System

An intelligent safety monitoring web app that predicts hazardous conditions using Machine Learning.

## Features

- Detects abnormal temperature
- Detects dangerous gas levels
- Detects fire/flame conditions
- Recommends actions to be taken
- Streamlit web interface
- Trained using historical sensor dataset

## Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- Joblib
- OpenPyXL

## Files

- app.py → Main web application
- sensor_model.pkl → Trained ML model
- label_encoder.pkl → Output label encoder
- requirements.txt → Dependencies

## How to Run

```bash
pip install -r requirements.txt
streamlit run app.py