# Phishing-Web

# Phishing Website Detection

This project is a web application that uses machine learning to detect whether a given website is safe or a phishing site. The app is built using Flask for the web interface and Scikit-learn for the machine learning model. The model is trained on various features extracted from URLs and website metadata.

## Features

- **Data Preprocessing:** The application uses Pandas to preprocess the data and extract features such as URL length, presence of suspicious characters, SSL certificate status, and more.
- **Machine Learning Model:** The project leverages Scikit-learn to train a classification model (e.g., Decision Tree, Random Forest) to predict whether a website is phishing or safe.
- **Web Interface:** The application provides a simple Flask-based interface where users can input a website URL to get a prediction.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/phishing-website-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd phishing-website-detection
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Train the model using your dataset:
    ```bash
    python train_model.py
    ```
2. Run the Flask application:
    ```bash
    python app.py
    ```
3. Open your browser and navigate to `http://127.0.0.1:5000` to use the web interface.

## Dataset

The dataset includes various features extracted from URLs and is labeled as either `phishing` (1) or `safe` (0). You can customize the dataset according to your needs.

## Technologies Used

- **Pandas** for data preprocessing and feature engineering
- **Scikit-learn** for model training and evaluation
- **Flask** for creating the web interface

## How It Works

1. The model is trained on a dataset containing features of URLs.
2. Users input a website URL in the web interface.
3. The application extracts features from the URL and uses the trained model to predict whether it is phishing or safe.
4. The prediction is displayed on the web interface.

## Contributing

Feel free to fork the repository and submit pull requests. Suggestions and improvements are welcome!

