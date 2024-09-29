# Flight Price Prediction Web App

This repository integrates Flask with a machine learning model to predict flight prices. The application allows users to input various features of a flight and receive an estimated price based on a trained machine learning model.

## Demo

You can view the deployed application at the following link:

[Flight Price Prediction App](https://flask-course-ml-project-2.onrender.com/)

## Features

- User-friendly web interface built with Flask
- Input fields for flight parameters
- Real-time flight price predictions based on a machine learning model
- Deployed on Render for easy access

## Installation

To install the required packages, run the following command in your terminal:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/anmol52490/flask-course-ml-project.git
   ```

2. Navigate to the project directory:
   ```bash
   cd flask-course-ml-project
   ```

3. Activate your virtual environment (if you have one):
   ```bash
   source venv/bin/activate   # On macOS/Linux
   .\venv\Scripts\activate    # On Windows
   ```

4. Run the Flask application:
   ```bash
   python app.py
   ```

5. Open your web browser and go to `http://127.0.0.1:5000` to access the application locally.

## Machine Learning Model

The model is trained on a dataset of flight prices and utilizes various features such as:

- Departure and arrival locations
- Flight duration
- Airlines
- Additional features relevant to pricing

The model's performance can be evaluated based on its accuracy and other metrics.

## Requirements

The project requires the following Python packages, listed in `requirements.txt`:

- Flask
- scikit-learn
- pandas
- numpy
- gunicorn

## Contributing

Feel free to contribute to this repository by submitting issues, suggestions, or pull requests. 
