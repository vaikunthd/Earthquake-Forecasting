# Earthquake Forecasting

This project focuses on predicting earthquake magnitudes using machine learning techniques. The analysis is performed on a dataset containing historical earthquake data.

## Project Overview

The Earthquake Forecasting project aims to:
- Analyze historical earthquake data
- Preprocess and prepare the data for machine learning
- Implement and compare various regression models
- Predict earthquake magnitudes based on available features

## Dataset

The project uses a dataset containing the following features:
- Date
- Time
- Latitude
- Longitude
- Type
- Depth
- Magnitude

## Methodology

1. **Data Preprocessing**:
   - Handling missing values
   - Converting date and time to datetime format
   - Feature engineering (e.g., extracting year, month, day, hour)

2. **Exploratory Data Analysis**:
   - Visualizing earthquake distributions
   - Analyzing correlations between features

3. **Model Implementation**:
   The project implements and compares the following regression models:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - XGBoost Regressor

4. **Model Evaluation**:
   - Using Mean Squared Error (MSE) and R-squared (R2) score for model assessment

## Requirements

To run this project, you'll need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Usage

1. Clone the repository
2. Install the required dependencies
3. Open and run the Jupyter Notebook `Earthquake Forecasting.ipynb`

## Results

The project compares the performance of different regression models in predicting earthquake magnitudes. Detailed results and visualizations can be found in the Jupyter Notebook.

## Future Work

- Incorporate additional features such as geological data
- Experiment with more advanced machine learning techniques
- Develop a web application for real-time earthquake magnitude predictions

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository and submit pull requests.

## License

This project is open-source and licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.

## Contact

For any queries or suggestions, please contact:
Vaikunth Desai - vdclassifier@gmail.com
