# Credit Score Predictor

This repository contains a credit score predictor that classifies given inputs into "poor," "standard," or "good" categories using the CatBoost algorithm. The predictor takes into account various input features, including annual income, monthly in-hand salary, age, employment type, number of credit cards, number of bank accounts, and occupation.

## Project Overview

The credit score predictor is built using the CatBoost machine learning algorithm, which is known for its robustness and ability to handle categorical features effectively. The predictor analyzes the provided input features and assigns a credit score category based on the classification model's predictions.

## Features

The credit score predictor offers the following features:

- **Input Features**: The predictor takes the following input features into account:
  - Annual income
  - Monthly in-hand salary
  - Age
  - Employment type
  - Number of credit cards
  - Number of bank accounts
  - Occupation

- **Credit Score Classification**: The predictor classifies the input into one of the following credit score categories:
  - Poor
  - Standard
  - Good

## Demo

A demo of the credit score predictor in action is available in GIF format. You can view the demo [here](demo.gif).

## Getting Started

To run the credit score predictor locally, follow these steps:

1. Create a Python 3.8 environment.
2. Install the required dependencies by running the following command:
   ```shell
   pip install -r requirements.txt
   ```
3. Run the Python application using the following command:
   ```shell
   python app.py
   ```
4. Access the credit score predictor application by visiting [http://127.0.0.1:5000/predictdata](http://127.0.0.1:5000/predictdata) or the appropriate localhost URL.

## Contributing

Contributions to this credit score predictor are welcome! If you have suggestions, bug reports, or would like to add new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the credit score predictor according to your requirements.

## Contact

For any questions or inquiries, please contact [your contact information].
