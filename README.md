# Iris Flower Species Prediction

## 📖 Project Overview

This project is a classic machine learning classification task that serves as an excellent introduction to data science and predictive modeling. The goal is to build a model that can accurately predict the species of an iris flower (`Iris-setosa`, `Iris-versicolor`, or `Iris-virginica`) based on four physical measurements of its sepals and petals.

We will use Python and popular data science libraries such as Pandas, Scikit-learn, and Seaborn to load, explore, visualize, and model the data. The final output is a trained k-Nearest Neighbors (k-NN) classifier that is evaluated on its predictive performance.

## 📊 Dataset Description

The project uses the well-known **Iris dataset**, a multivariate dataset introduced by the British statistician and biologist Ronald Fisher in 1936. It is often referred to as the "Hello, World!" of machine learning datasets.

The dataset contains 150 samples from three species of Iris flowers. There are 50 samples for each species.

### Features (Predictor Variables):

The following four features are included for each sample, measured in centimeters:

1.  **`SepalLengthCm`**: The length of the sepal.
2.  **`SepalWidthCm`**: The width of the sepal.
3.  **`PetalLengthCm`**: The length of the petal.
4.  **`PetalWidthCm`**: The width of the petal.

### Target Variable (What we want to predict):

1.  **`Species`**: The species of the iris flower. It has three distinct classes:
    *   `Iris-setosa`
    *   `Iris-versicolor`
    *   `Iris-virginica`

## ⚙️ Environment Setup and Installation

To ensure a clean and reproducible environment, it is highly recommended to use a virtual environment. The following steps will guide you through setting up the project using `venv`.

### Prerequisites

*   **Python 3.7+** installed on your system.
*   **Git** for cloning the repository.

### Step-by-Step Instructions

**1. Clone the Repository**

First, clone this repository to your local machine using Git:
```bash
git clone git@github.com:moro24/ml_iris_prediction.git
cd ml_iris_prediction
```

**2. Create a `requirements.txt` file**

Before setting up the environment, create a file named `requirements.txt` in the root of your project directory. This file will list all the necessary Python libraries.

Copy the following into your `requirements.txt` file:
```
pandas
scikit-learn
matplotlib
seaborn
jupyterlab
```

**3. Create a Virtual Environment**

From the root directory of the project, create a new virtual environment named `venv`:
```bash
python -m venv venv
```
This command creates a `venv/` folder in your project, which will contain a private copy of Python and its packages.

**4. Activate the Virtual Environment**

You must activate the environment before you can install packages into it. The activation command is different for Windows and macOS/Linux.

*   **On Windows (Command Prompt or PowerShell):**
    ```bash
    venv\Scripts\activate
    ```

*   **On macOS and Linux (bash/zsh):**
    ```bash
    source venv/bin/activate
    ```

After activation, you will see `(venv)` at the beginning of your command prompt, indicating that the virtual environment is active.

**5. Install Required Libraries**

With the virtual environment active, install all the required libraries listed in `requirements.txt` using a single command:
```bash
pip install -r requirements.txt
```
This command reads the file and installs the specific versions of each library needed for the project.

**6. Launch Jupyter Noteboo**

Once the installation is complete, you can start Jupyter Lab to run the project notebook:
```bash
jupyter-notebook
```
This will open a new tab in your web browser, where you can navigate to the `.ipynb` notebook file and start working.

**7. Deactivating the Virtual Environment**

When you are finished working on the project, you can deactivate the environment by simply typing:
```bash
deactivate
```