# Medical Diagnosis Using AI & ML
https://medical-diagnosis-using-ai-mltabreadme-ov-file-njqomhsspr4dmjl.streamlit.app/
## Table of Contents
- [Description](#description)
- [Technologies Used](#technologies-used)
- [Installation Steps](#installation-steps)
- [Usage](#usage)
- [Models](#models)
- [Contributing](#contributing)

## Description
This project is a Streamlit web application that predicts the likelihood of a patient having various diseases based on user-provided health data. It uses pre-trained machine learning models to make predictions for diabetes, heart disease, Parkinson's disease, lung cancer, and hypothyroidism.

## Technologies Used
- Python 3.6 or higher
- Streamlit
- Scikit-learn
- Pickle
- streamlit-option-menu

## Installation Steps

1) Clone the Repository:
```bash
git clone <repository_url>
cd <repository_directory>
```

2) Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Linux/macOS

venv\Scripts\activate  # On Windows
```

3) Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage

1) Run the Streamlit application:
```bash
streamlit run app.py
```
Replace `app.py` with the actual name of your main script if it's different.

2) Open the application in your web browser:
Streamlit will provide a URL (usually `http://localhost:8501`) to access the application.

3) Select a disease to predict from the dropdown menu.

4) Enter the required health data in the input fields. Tooltips are provided to explain each field.

5) Click the **"Test Result"** button to get the prediction. The result will be displayed on the screen.

## Models
The application uses pre-trained machine learning models stored in `.sav` files. These files should be placed in a directory named **Models** within the main project directory. Here's a list of the models used:

- `diabetes_model.sav`: Diabetes prediction model
- `heart_disease_model.sav`: Heart disease prediction model
- `parkinsons_model.sav`: Parkinson's disease prediction model
- `lungs_disease_model.sav`: Lung cancer prediction model
- `Thyroid_model.sav`: Hypothyroidism prediction model

## Contributing
Contributions are welcome! Please follow these steps:

1) Fork the repository.
2) Create a new branch for your feature or bug fix.
3) Make your changes and commit them with clear, descriptive messages.
4) Test your changes thoroughly.
5) Submit a pull request.
