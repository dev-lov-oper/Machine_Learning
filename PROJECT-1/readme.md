A Django-based machine learning web application that predicts car prices by analyzing various input features using a Linear Regression model.

📌 Features
Interactive Web Interface: User-friendly UI built with HTML,CSS,JS to input car specifications easily.

ML Price Prediction: Real-time car price estimation powered by a trained Linear Regression algorithm.

Data Preprocessing & Feature Engineering: Preprocessed inputs (mileage, engine size, fuel type, vehicle age, brand, etc.) formatted for accurate model inference.

Responsive Layout: Simple form submission with immediate price output display.

🛠️ Tech Stack
Backend & Web Framework: Python 3.x, Django

Machine Learning & Data Science: scikit-learn, pandas, numpy

Data Visualization (EDA): matplotlib, seaborn

Frontend: HTML5, CSS3, JavaScript (Django Templates)

📊 How It Works
Exploratory Data Analysis (EDA): Analyzed dataset distributions, correlation between features, and handled missing/outlier values.

Model Training: Trained a Multiple Linear Regression model (scikit-learn) on car dataset parameters such as year, kilometers driven, fuel type, transmission, and horsepower.

Inference Pipeline: The Django views.py accepts user input from the HTML form, applies necessary scaling/encoding, and passes features into the saved model file to return an estimated price

I will be deploying the application soon...
