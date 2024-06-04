## Background
Spam text messages are a rampant concern in the Philippines  
- 1 in 4 Filipinos become a victim of schemes like spam messages (National ICT Household Survey, 2019)  
- Alleged correlation with contact tracing forms  
- Globe has blocked 1.3 billion scam texts during a 9-month span in 2022

## Goal
This project aims to contribute to the solution by creating a machine learning model to accurately detect scam/spam text messages in the Philippines.

## Method
The model was trained with the Naive-Bayes classification algorithm using existing datasets with labeled SMS messages for text classification

## Results
The accuracy score of the initial model with default parameters is 99.28%  
The accuracy score of the optimized model after hyperparameter tuning is 99.50%

## Running Our App Locally

```bash
cd DeployModel
python manage.py runserver
```

Your Django application is now available at `http://localhost:8000`.
