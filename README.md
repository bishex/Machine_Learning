# Phishing Detection System

## Table of Contents

- [Project Description](#project-description)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Model Selection and Evaluation](#model-selection-and-evaluation)
- [About the Author](#about-the-author)
- [License](#license)

## Project Description

The Phishing Detection System is a web application that uses machine learning to predict whether a given URL is a phishing site. The application is built using Flask for the backend, with HTML5 and CSS for the frontend.


## Dependencies

This application requires the following Python libraries, which can be installed by navigating to the project directory and running `pip install -r requirements.txt`:

- Flask
- joblib
- numpy
- python-whois
- scikit-learn

## Usage

You can run the application by executing the `app.py` script:

```bash
python app.py
```
This will start a local server and serve the Phishing Detection System on localhost:5000.

## Model Selection and Evaluation

we use RandomForest model, because it significantly improved the performance of our phishing detection.

![Model Evaluation Image](/static/myplot.png)

## developers
This project is developed by BIT cyberSecurity students 