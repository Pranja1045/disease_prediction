# Disease Prediction System

## Overview

The Disease Prediction System is a web application built with Python, Streamlit, and TensorFlow/Keras. It provides predictions for three types of diseases using machine learning models:

- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

The app allows users to input relevant medical data and receive predictions about the likelihood of the diseases mentioned above.

## Features

- **User-Friendly Interface**: Simple and intuitive web interface using Streamlit.
- **Multi-Disease Support**: Supports prediction for diabetes, heart disease, and Parkinson's.
- **Pre-Trained Models**: Leverages pre-trained models saved in the `my_models` directory.
- **Standardized Input**: Inputs are standardized using StandardScaler before predictions.
- **Error Handling**: Provides detailed error messages for invalid inputs or missing model files.

## Prerequisites

Ensure you have the following installed:

- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Pranja1045/disease-prediction-system.git
cd disease-prediction-system
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
## Directory Structure
``` bash
.
├── app.py                  # Main Streamlit application
├── my_models               # Directory for storing pre-trained models
│   ├── model_diabetes_data.h5
│   ├── model_heart_data.h5
│   └── model_parkinsons_data.h5
├── requirements.txt        # Python dependencies
├── submission.ipynb        # Jupyter notebook for model training and evaluation
└── README.md               # Project documentation
```
## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch:
``` bash
git checkout -b feature-name
```
3. Commit your changes:
``` bash
git commit -m "Add a new feature"
```
4. Push the branch:
``` bash
git push origin feature-name
```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
- For questions or feedback, please contact:
- Name: Pranjal Sharma
- GitHub: Pranja1045

   

