# ML_Projects

This repository contains a collection of university projects focused on applying various machine learning techniques to diverse datasets. Each project is designed to address specific predictive modeling challenges using different algorithms.

## Table of Contents

- [Projects Overview](#projects-overview)
  - [1. Admission Status Prediction](#1-admission-status-prediction)
  - [2. Car Price Prediction](#2-car-price-prediction)
  - [3. Forest Cover Type Prediction](#3-forest-cover-type-prediction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Projects Overview

### 1. Admission Status Prediction

- **Summary**: Developed a predictive model to estimate the likelihood of a student's admission into a graduate program based on features such as GRE scores, TOEFL scores, university ratings, and more.
- **Methods Used**: Logistic Regression.

  Logistic Regression is a statistical method for analyzing datasets in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). In this project, Logistic Regression was employed to model the probability of admission.

### 2. Car Price Prediction

- **Summary**: Created a model to predict the selling prices of used cars based on attributes like mileage, make, model, year of manufacture, and other relevant features.
- **Methods Used**: Linear Regression.

  Linear Regression is a linear approach to modeling the relationship between a dependent variable and one or more independent variables. It assumes a linear relationship between the input variables and the single output variable. This project utilized Linear Regression to estimate car prices based on historical data.

### 3. Forest Cover Type Prediction

- **Summary**: Built a classification model to identify the type of forest cover (the predominant kind of vegetation) from cartographic variables such as elevation, aspect, slope, and soil type.
- **Methods Used**: Ensemble Learning techniques and neural networks, including:

  - **Random Forest** (Best performance, RMSE: 0.13): An ensemble learning method that operates by constructing multiple decision trees during training and outputting the mode of the classes for classification tasks. It improves predictive accuracy and controls overfitting by averaging multiple deep decision trees trained on different parts of the same dataset.
  
  - **XGBoost** (RMSE: 1.01): Stands for Extreme Gradient Boosting. It's an optimized distributed gradient boosting library designed to be highly efficient, flexible, and portable. XGBoost implements machine learning algorithms under the Gradient Boosting framework.

  - **AdaBoost** (RMSE: 7.84): Short for Adaptive Boosting, this algorithm combines multiple "weak" classifiers to create a "strong" classifier. Each iteration focuses more on samples that were previously misclassified.

  - **LSTM (Long Short-Term Memory)** (RMSE: 110.85): A type of recurrent neural network (RNN) capable of learning long-term dependencies. Although LSTMs are typically used for sequential data, they were applied here as an experimental approach.

## Getting Started

To explore and run these projects locally, follow the steps below.

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Necessary Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`, `tensorflow`

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RahimaKarimova/ML_Projects.git
   cd ML_Projects
   ```

2. **Install Dependencies**:

   It's recommended to use a virtual environment:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

   Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

   > **Note**: If `requirements.txt` is not provided, manually install the necessary libraries:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xgboost tensorflow
   ```

3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

   Navigate to the desired project folder and open the corresponding `.ipynb` file.

## Contributing

Contributions are welcome! If you'd like to enhance any of the projects or add new ones:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeatureName`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeatureName`
5. Open a pull request.

Please ensure your contributions align with the repository's objectives and maintain consistency in code style and documentation.

## Contact

For any questions or suggestions, feel free to reach out:

- **Name**: Rahima Karimova
- **GitHub**: [RahimaKarimova](https://github.com/RahimaKarimova)

---

*Note: Replace `[your.email@example.com](mailto:your.email@example.com)` with your actual email address.*
