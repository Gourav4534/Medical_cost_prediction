# Medical Cost Prediction

Welcome to the Medical Cost Prediction project! This project aims to predict medical costs based on various factors such as age, BMI, smoking status, and more. This README will guide you through the project's setup, usage, and other important details.

## Project Overview

The Medical Cost Prediction project utilizes a dataset to predict the medical costs for individuals based on their characteristics. The dataset includes information on age, number of children, BMI, sex, smoking status, and region, with the goal of predicting the medical charges.

### Dataset

The dataset consists of approximately 1,300 records with the following features:

- **age**: Age of the individual
- **children**: Number of children the individual has
- **bmi**: Body Mass Index of the individual. Categories include:
  - Underweight: BMI < 18.5
  - Normal: 18.5 - 24.9
  - Overweight: 25.0 - 29.9
  - Obese: BMI > 30.0
- **sex**: Sex of the individual (Male or Female)
- **smoking**: Whether the individual is a smoker (Yes or No)
- **region**: Region of the individual (Northeast, Northwest, Southeast, Southwest)
- **charges**: Target variable representing the medical charges

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/medical-cost-prediction.git
    cd medical-cost-prediction
    ```

2. **Create a Virtual Environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**:

    ```bash
    python application.py
    ```

2. **Access the Web Interface**:
   Visit [http://localhost:5000](http://localhost:5000) in your web browser to use the application and make predictions.

3. **Deployment**:

   The application is deployed and accessible online. Visit [Medical Cost Prediction Web Application](https://medical-cost-prediction-99x5.onrender.com/prediction) to interact with the deployed version.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request with your changes. Ensure that you adhere to the project's coding standards and include appropriate tests for your modifications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- **Gourav Yadav** - [GitHub Profile](https://github.com/Gourav4534)
