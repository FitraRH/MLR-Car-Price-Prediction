
# Car Price Prediction Using Multiple Linear Regression

`Author : Fitra Ramdhan H`
`Undergraduate Informatics AI student at President University`

This project uses Multiple Linear Regression (MLR) to predict car prices based on various features of a car, such as model, year, mileage, fuel type, etc.

## Project Structure

- **`MLR.ipynb`**: The Jupyter Notebook containing the implementation of the MLR model.
- **`dataset/toyota.csv`**: The dataset used for training and testing the model. It contains car features and their respective prices.

## Dataset

The dataset `toyota.csv` includes the following columns:

- `model`: The model of the car.
- `year`: The manufacturing year of the car.
- `transmission`: Type of transmission (e.g., Automatic, Manual).
- `mileage`: The mileage of the car.
- `fuelType`: The type of fuel (e.g., Petrol, Diesel).
- `tax`: Tax applied to the car.
- `mpg`: Miles per gallon (fuel efficiency).
- `engineSize`: Size of the engine.
- `price`: The target variable, representing the car's price.

## Steps in the Notebook

### # Install Libraries

### # Import Libraries

### # 1. Import Data

### # 2. Data Understanding

### # 3. Cleaning Data

### # 4. Exploratory Data Analyst

### # 5. Label Encoder 

### # 6. Preparation Data

### # 7. Training & Evaluation Data

### # 8. Testing

### Running the Project

1. Open the `MLR.ipynb` file in Jupyter Notebook.
2. Execute each cell to load the dataset, preprocess the data, train the model, and make predictions.
3. Modify the `input_data` dictionary in the notebook to test the model with your own car specifications.

### Custom Input Example

You can customize the input data for prediction by modifying the dictionary in the notebook, as shown:

```python
input_data = {
    'model': 'Yaris',
    'year': 2019,
    'transmission': 'Automatic',
    'fuelType': 'Petrol',
    'mileage': 1401,
    'tax': 150,
    'mpg': 76.3,
    'engineSize': 1.5
}
```

### Output Example

The model will output the estimated price of the car based on the given inputs:

```
Car price estimation: Rp. 175000000
```

## Notes

- Ensure the dataset is available in the `dataset/` folder when running the notebook.
- Modify the notebook as needed to experiment with different models or preprocess data differently.

## Author

This project is designed for educational purposes to demonstrate how to use Multiple Linear Regression for predictive modeling.
