Iris Classification API (Machine Learning + Flask + Docker)

This project demonstrates a complete deployment workflow for a Machine Learning model using:

scikit-learn for training

Flask for serving predictions

Docker for containerization

cURL or frontend apps for testing

Features

Predicts Iris flower class (0, 1, or 2)

REST API endpoint: /predict

Lightweight and fast API

Works locally and inside Docker containers

Ready for deployment on Render, Railway, Azure, AWS, etc.

Step 1: Install dependencies
pip install -r requirements.txt

Step 2: Start the API
python app.py

Running on http://127.0.0.1:5000/

Using curl (Windows one-line command)
curl -X POST http://127.0.0.1:5000/predict -H "Content-Type: application/json" -d "{\"features\": [5.1, 3.5, 1.4, 0.2]}"

License: This project is open-source. You may modify or extend it for learning or deployment practice.

