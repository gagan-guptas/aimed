## Project Overview
The **Edunet Project** is a machine learning-based medical prediction system that aims to detect diseases such as diabetes, heart disease, thyroid disorders, Parkinson's disease, and lung cancer. It utilizes preprocessed datasets and trained machine learning models to provide predictions.

## Features
- **Disease Prediction**: Predicts multiple diseases using trained models.
- **Preprocessed Datasets**: Cleaned and structured medical datasets.
- **Machine Learning Models**: Pretrained models for quick predictions.
- **Application Script**: `app.py` for deployment (potentially a web app or API).

## Project Structure
```
Edunet_project/
│── app.py                 # Main application script
│── Datasets/              # Contains dataset CSV files
│   ├── diabetes_data.csv
│   ├── heart_disease_data.csv
│   ├── hypothyroid.csv
│   ├── parkinson_data.csv
│   ├── survey_lung_cancer.csv
│── Models/                # Trained ML models (.sav files)
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── lungs_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── Thyroid_model.sav
│── Notebooks/             # Jupyter notebooks for training and analysis
│   ├── Heart_Disease_Prediction.ipynb
│   ├── Lung_Cancer.ipynb
│   ├── Parkinson's_Disease_Detection.ipynb
│   ├── Thyroid.ipynb
```

## Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install -r requirements.txt
```

### Running the Application
To run the prediction system:
```bash
python app.py
```
This will launch the application (if it's a web app, check `localhost` in your browser).

## Dataset Details
- **Diabetes Dataset**: Used to train the diabetes model.
- **Heart Disease Dataset**: Used for heart disease prediction.
- **Thyroid Dataset**: Processed data for thyroid condition prediction.
- **Parkinson’s Disease Dataset**: Data for early Parkinson’s detection.
- **Lung Cancer Dataset**: Survey-based dataset for lung cancer risk.

## Contributing
If you'd like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

