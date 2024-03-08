**README.md**

## Video Game Sales Prediction Model

This repository contains code for building and deploying a machine learning model to predict global sales of video games. The model is trained on a dataset containing information about various video games including their platform, genre, publisher, and regional sales figures.

### Files Description:

- **model.py**: This file contains the code for training the machine learning model. It loads the dataset, preprocesses it, trains a Random Forest Regressor, and saves the trained model as a pickle file.
  
- **app.py**: This file contains the Flask application for deploying the trained model. It loads the pickled model, creates an API endpoint for making predictions, and serves a basic HTML interface for user interaction.

### Dependencies:

- Python 3.x
- Flask
- NumPy
- Pandas
- scikit-learn

### Usage:

1. **Training the Model**:
   - Run the `model.py` script. This will preprocess the dataset, train the Random Forest Regressor, and save the trained model as `model.pkl`.

2. **Deployment**:
   - Run the `app.py` script. This will start a Flask web application locally, allowing users to interact with the trained model.



### Notes:

- The dataset used for training the model is `vgsales.csv`.
- The trained model is saved as `model.pkl`.
- The Flask application serves a basic HTML interface for making predictions based on user input.

For any questions or issues, please feel free to contact the repository owner.
