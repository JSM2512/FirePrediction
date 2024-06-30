# FirePrediction

A machine learning project aimed at predicting the occurrence of fires using various models and techniques.

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
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
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


- `.ebextensions/`: Configuration files for AWS Elastic Beanstalk.
- `models/`: Pre-trained machine learning models.
- `notebooks/`: Jupyter notebooks for data preprocessing and model training.
- `templates/`: HTML templates for the web interface.
- `application.py`: The main application file.
- `requirements.txt`: List of dependencies required for the project.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.

## License

This project is licensed under the MIT License.
