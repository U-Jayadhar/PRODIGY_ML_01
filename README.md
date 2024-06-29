# **PRODIGY_ML_01**

## Task-1 of ML Internship at Prodigy Infotech

_Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms._

## Program Structure

- `README.md`: Project documentation.
- `ML Task-1`: Contains all the files of the project
  - `train.csv`: The dataset used for training the model (you need to provide this file).
  - `t-1_model.ipynb`: Jupyter Notebook containing the code for training and evaluating the linear regression model.
  - `test.csv`: The test dataset used for making predictions.
  - `predicts.csv`: The output file with predicted house prices for the test dataset.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/U-Jayadhar/PRODIGY_ML_01.git
   ```
2. Navigate to the project directory:
   ```sh
   cd PRODIGY_ML_01
   ```

## Usage

1. Ensure you have the `train.csv` file in the project directory.
2. Open and run the Jupyter Notebook `t-1_model.ipynb` to train the model and make predictions:
   ```sh
   jupyter notebook t-1_model.ipynb
   ```
3. The predictions of `test.csv` will be saved in `predicts.csv`.

## Model

The model uses the following features to predict house prices:

- `GrLivArea`: Above ground living area square footage.
- `BedroomAbvGr`: Number of bedrooms above ground.
- `FullBath`: Number of full bathrooms.
- `TotalBsmtSF`: Total square feet of the basement area.
- `1stFlrSF`: First floor square feet.
- `2ndFlrSF`: Second floor square feet.
- `HalfBath`: Number of half bathrooms.
- `GarageArea`: Size of the garage in square feet.
- `BsmtFullBath`: Number of full bathrooms in the basement.
- `BsmtHalfBath`: Number of half bathrooms in the basement.

### Training and Evaluation

The `train.csv` dataset is split into training and testing sets. The linear regression model is trained on the training set and evaluated on the testing set. The model's performance is measured using Mean Squared Error (MSE).

## Results

- **Mean Squared Error (MSE):** 1827824884.344168
- The `predicts.csv` is the output file with predicted house prices for the `test.csv` dataset.

## Acknowledgments

This project is based on the [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) competition on Kaggle.

## Contact

For any queries or suggestions, feel free to contact me

Linkedin: [Jayadhar Ummadingu](https://www.linkedin.com/in/jayadhar-ummadisingu-2a825b25a/)

E-mail: jummadis@gitam.in
