# Boston Housing Price Prediction

This project demonstrates a machine learning pipeline for predicting housing prices in Boston using the Boston Housing Dataset. It includes both model development and a user interface for interaction.

## Contents

- `BostonHousing.ipynb`: Builds and trains a regression model using Scikit-learn.
- `BostonInterface.ipynb`: Provides a graphical user interface (GUI) for making predictions using the trained model.

---

## 1. `BostonHousing.ipynb`

### Description
This notebook covers the complete workflow for predicting housing prices:
- Loading the Boston Housing Dataset
- Data preprocessing and exploration
- Feature selection and transformation
- Model training using Linear Regression
- Evaluation of model performance (R², MSE, etc.)
- Saving the trained model for later use (`joblib`)

### Libraries Used
- `pandas`
- `numpy`
- `seaborn`, `matplotlib`
- `sklearn` (for model building and evaluation)
- `joblib` (to save the model)

---

## 2. `BostonInterface.ipynb`

### Description
This notebook creates a basic interface using `ipywidgets` for user interaction:
- Loads the saved model from the training notebook
- Allows the user to input feature values through sliders or text fields
- Displays the predicted housing price based on user inputs

### Libraries Used
- `ipywidgets`
- `IPython.display`
- `joblib`
- `sklearn`
- `numpy`

---

## How to Run

1. **Install Dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn ipywidgets joblib
   ```

2. **Run `BostonHousing.ipynb`**:
   - Trains the model
   - Saves it as `boston_model.pkl`

3. **Run `BostonInterface.ipynb`**:
   - Loads the saved model
   - Allows you to input values and get a predicted price

---

## Requirements

- Python 3.7+
- Jupyter Notebook
- All required libraries as listed above

---

## License

This project is open-source and free to use for educational purposes.
