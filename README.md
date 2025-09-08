# Wine Quality Prediction using Machine Learning (OOP-based)

This project predicts the quality of red wine based on various chemical features using a machine learning model implemented with Object-Oriented Programming (OOP) in Python.

## Project Objective

To develop a wine quality prediction system using a clean and modular codebase that follows OOP principles. The goal is to accurately classify wine quality using chemical properties like acidity, alcohol, sugar, etc.

## Project Structure

OOP Project

├── winequality-red.csv # Dataset
├── main.py # Main script to run all modules
├── wine_model.pkl # Saved trained model
├── OOP Project.ipynb # Jupyter notebook for development
│
├── data_collector.py # Class: Loads dataset
├── data_understanding.py # Class: Displays dataset info
├── data_preprocessing.py # Class: Cleans and splits data
├── model_trainer.py # Class: Trains the ML model
├── model_storage.py # Class: Saves/loads model
├── visualiser.py # Class: Handles data visualization
└── README.md # Project documentation

## Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Object-Oriented Programming (OOP)

## Machine Learning

- **Algorithm:** Support Vector Machine (SVM)
- **Target variable:** 'quality'
- **Features used:** 11 physicochemical attributes (e.g. alcohol, acidity, pH)

## How to Run the Project

1. Make sure Python and required libraries are installed.
2. Run 'main.py' to execute:
   - Data loading
   - Preprocessing
   - Visualization
   - Model training
   - Model saving
3. Trained model will be saved as 'wine_model.pkl'.

## Future Improvements

- Add GUI for user interaction
- Use other ML algorithms like Random Forest or XGBoost
- Add model evaluation metrics (precision, recall)
- Perform hyperparameter tuning
