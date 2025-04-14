# ml-options-pricing
This project applies machine learning techniques to estimate the prices of options contracts based on multiple features. The performance of the trained models is benchmarked against the traditional Black-Scholes model to assess improvements in accuracy.

## Overview
The goal of this project is to improve the pricing accuracy of options using data-driven models. It leverages the following machine learning techniques:

LightGBM: A gradient boosting framework using tree-based learning.

Neural Networks: Deep learning models for capturing non-linear patterns.

Support Vector Machines (SVM): Regression-based supervised learning.

The dataset consists of historical data for 98 call options collected from Iran’s Options Market over a period of three years.

Project Structure
graphql
Copy
Edit
ml-options-pricing/
├── ml_option_pricing.ipynb       # Main Jupyter notebook with analysis
├── option_prices_data.xlsx       # Historical options data
├── best_SVR.sav                  # Trained SVM model (saved)
├── best_lgb.sav                  # Trained LightGBM model (saved)
├── NN_learning_curve.png         # NN training curve visualization
├── NNsklearn_learning_curve.png  # Learning curve with sklearn
├── errors_boxplot.png            # Boxplot of prediction errors
├── errors_dist.png               # Distribution plot of errors
├── errors_tosifi.csv             # Evaluation metrics for all models
├── README.md                     # Project documentation
└── LICENSE                       # MIT License file
Installation
Prerequisites
Python 3.8 or above

Git

Setup Steps
Clone the repository:
```bash
git clone https://github.com/Reckonchamp12/ml-options-pricing.git
cd ml-options-pricing
Create and activate a virtual environment:

python -m venv venv
On Windows:

venv\Scripts\activate
On macOS/Linux:

source venv/bin/activate
Install the required dependencies:

If requirements.txt is available:

pip install -r requirements.txt
If not, install manually:

pip install numpy pandas scikit-learn lightgbm matplotlib jupyter
Usage
Launch Jupyter Notebook:

jupyter notebook
Open the ml_option_pricing.ipynb notebook and run all cells sequentially to:
```

Preprocess the dataset

Train and evaluate LightGBM, Neural Network, and SVM models

Compare results against Black-Scholes pricing

Visualize learning curves and error distributions

## Results
The machine learning models demonstrated enhanced accuracy over the classical Black-Scholes model. Learning curves and error plots provided insights into model performance and generalization capabilities.

## Contributing
Contributions are welcome. To contribute:

## Fork this repository

Create a new branch:

```bash

git checkout -b feature/YourFeature
Commit your changes:


git commit -m "Add feature: YourFeature"
Push to your fork:


git push -u origin feature/YourFeature
Open a pull request with a clear description of your changes.
```

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
GitHub: Reckonchamp12

Email: rayrahuldw@gmail.com

