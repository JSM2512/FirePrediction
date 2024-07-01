# Algerian Forest Fire Prediction Website

FirePrediction is a machine learning project designed to forecast the occurrence of forest fires using advanced modeling techniques and data-driven insights. Leveraging the Algeria Forest Fire Dataset sourced from Kaggle, this project aims to develop predictive models that can effectively anticipate fire incidents based on historical data and environmental variables.

#### Algeria Forest Fire Dataset : https://www.kaggle.com/datasets/nitinchoudhary012/algerian-forest-fires-dataset


## Methodology
The project employs a multifaceted approach to model development, beginning with exploratory data analysis (EDA) and preprocessing tasks in Jupyter Notebooks. Data preprocessing involves handling missing values, feature scaling, feature selection and possibly feature engineering to extract more meaningful insights from the dataset.

Following preprocessing, multiple machine learning algorithms are explored using scikit-learn (SKLearn) within Jupyter Notebooks. Various models such as Ridge Regression, RidgeCV, Lasso, LassoCV, ElasticNet, ElasticNetCV are trained and evaluated to identify the most effective model for fire prediction. 

Model Accuracy based on r2-Score : 98.4% 

![image](https://github.com/JSM2512/FirePrediction/assets/49087609/91c5351a-9a93-4559-a6cc-3c956c56d156)

- This Linear relation between the Ground Truth and Predicted values of test data shows model is performing well.


## Explore Notebooks:
[![EDA Notebook](https://img.shields.io/badge/Exploratory%20Data%20Analysis-Explore-green)](notebooks/Algerian%20Forest%20EDA%20and%20Data%20CleaningRidge,%20Lasso%20Regression.ipynb)
[![Model Training Notebook](https://img.shields.io/badge/Model%20Training-Train-blue)](notebooks/Algerian%20Forest%20Model%20Training%20Cleaned%20LASSO%20RIDGE%20ELASTICNET.ipynb)

## Tech Stack
- Flask
- Jupyter Notebook
- SKLearn
- Python
- HTML
- CSS

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/JSM2512/FirePrediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd FirePrediction
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv venv1
    source venv1/bin/activate  # On Windows use `venv1\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    python application.py
    ```
2. Access the web interface at `http://127.0.0.1:5000`.

## Project Structure
```
FirePrediction/
├── .ebextensions/
├── models/
│   ├── model1.pkl
│   ├── model2.pkl
│   └── ...
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── ...
├── templates/
│   ├── index.html
│   ├── result.html
│   └── ...
├── venv/
├── application.py
├── requirements.txt
└── README.md
```

- `.ebextensions/`: Configuration files for AWS Elastic Beanstalk.
- `models/`: Pre-trained machine learning models.
- `notebooks/`: Jupyter notebooks for data preprocessing and model training.
- `templates/`: HTML templates for the web interface.
- `application.py`: The main application file.
- `requirements.txt`: List of dependencies required for the project.

## Contributions

Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.
