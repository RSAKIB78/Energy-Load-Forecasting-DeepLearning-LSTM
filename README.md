# Electric Energy Consumption Load Forecasting

This project simulates a scenario to demostrate how energy providers can use predictive modeling to forecast short-term load demand using historical consumption data.

# Data Dictionary

- nat_demand: National electricity load
- T2M: Temperature at 2 meters
- QV2M: Relative humidity at 2 meters
- TQL: Liquid precipitation
- W2M: Wind speed at 2 meters

And after the underscore is the city

- toc: Tocumen, Panama city
- san: Santiago city
- dav: David city

The rest of variables:

- Holiday_ID: Unique identification number integer
- holiday: Holiday binary indicator (1=holiday, 0=regular day)
- school: School period binary indicator (1=school, 0=vacations)


# Machine Learning Model Training and Evaluation

The project makes use of training and evaluating machine learning models using Python libraries such as Pandas, NumPy, Scikit-learn, and TensorFlow.

## Project Structure

Files included in the project:

- `main.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `continuous dataset.csv`: The main dataset used for training and testing the models.
- `LICENSE`: MIT License for the project.
- `README.md`: This file.

Project Outline:

- Data Ingestion
- Data Exploration
- Feature Selection
- Modeling
- Model Evaluation

## Dependencies

The following Python libraries are required to run the notebook:

- pandas
- numpy
- scikit-learn
- tensorflow
- matplotlib

You can install the required libraries using pip:

```sh
pip install pandas numpy scikit-learn tensorflow matplotlib
```

# Usage
Open the main.ipynb file in Jupyter Notebook or JupyterLab.
Run the cells sequentially to preprocess the data, train the models, and evaluate their performance.

Models Used
LSTM (Long Short-Term Memory)


# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Authors
- M S Sakib Rahman
- Aviel Jailal