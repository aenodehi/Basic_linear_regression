# Project Weight-Height predict with Linear Regression

## Overview

This project focuses on predicting the height of individuals based on their weight using a Linear Regression model. The dataset contains weight and height observations, which are used to train and evaluate the model. The goal is to accurately predict the height, which can be useful in various applications such as health and fitness tracking.

## Dataset

### Attribute Information:

- **Weight**: Weight of the individual in pounds (lbs).
- **Height**: Height of the individual in inches (in).

## Machine Learning Model

The following machine learning model is implemented and evaluated in this project:

1. **Linear Regression Model**

## Repository Structure

- **Basic_linear_regression_dataset**: Contains the dataset used for training and testing the model.
- **Basic_linear_regression.ipynb**: Jupyter notebook for exploratory data analysis (EDA) and model training.
- **Dockerfile**: Dockerfile for containerizing the project.
- **compose.yml**: Docker Compose file for orchestrating the project's containers.
- **.gitignore**: Specifies files and folders to be ignored by Git.

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/aenodehi/Basic_linear_regression.git
   cd Basic_linear_regression
   ```

2. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

3. **Open and run the notebook**:
   - Navigate to the notebook file (e.g., `Basic_linear_regression.ipynb`) and run the cells to train and evaluate the model.

## Docker Setup

If you prefer to run the project in a Docker container, follow these steps:

1. **Build the Docker image**:
   ```bash
   docker build -t basic_linear_regression .
   ```

2. **Run the Docker container**:
   ```bash
   docker run -p 8888:8888 basic_linear_regression
   ```

3. **Access the Jupyter Notebook**:
   - Open your browser and go to `http://localhost:8888`.

## Docker Compose

For a more complex setup, you can use Docker Compose:

1. **Start the services**:
   ```bash
   docker-compose up
   ```

2. **Access the Jupyter Notebook**:
   - Open your browser and go to `http://localhost:8888`.

## Results

The performance of the Linear Regression model is evaluated using metrics such as Mean Squared Error (MSE), R-squared, and others. The results are summarized in the notebook, and the model's accuracy is highlighted.
