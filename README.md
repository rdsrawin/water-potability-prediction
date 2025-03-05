# Water Quality Prediction Using Machine Learning

## Description
This project aims to predict the potability of water using machine learning models. By analyzing various physicochemical properties of water samples, the model determines whether the water is safe for drinking. The dataset consists of multiple water quality indicators, and different machine learning algorithms are employed to classify water as potable or non-potable.

## Dataset
The dataset used in this project is `water_potability.csv`, which contains information about different water quality parameters. The key attributes include:

- **pH**: Measures the acidity or basicity of the water.
- **Hardness**: Represents the amount of dissolved calcium and magnesium.
- **Solids**: Total dissolved solids (TDS) in the water.
- **Chloramines**: The concentration of disinfectants used in water treatment.
- **Sulfate**: Amount of sulfate ions present.
- **Conductivity**: Indicates the ability of water to conduct electricity.
- **Organic Carbon**: The presence of organic compounds in water.
- **Trihalomethanes**: Byproducts of water chlorination.
- **Turbidity**: The cloudiness of the water.
- **Potability**: The target variable (1 for potable, 0 for non-potable).

## Features
- **Data Preprocessing**: Handling missing values, scaling, and feature engineering.
- **Exploratory Data Analysis (EDA)**: Visualizing distributions, correlations, and trends.
- **Machine Learning Models**: Training classifiers such as Logistic Regression, Decision Trees, Random Forest, and Neural Networks to predict potability.
- **Model Evaluation**: Using metrics like accuracy, precision, recall, and F1-score to assess performance.

## Installation & Dependencies
To run the project, install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

To execute the notebook:

```bash
jupyter notebook water_quality.ipynb
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/water-quality-prediction.git
   cd water-quality-prediction
   ```
2. Load the dataset (`water_potability.csv`).
3. Preprocess and clean the data.
4. Train machine learning models on the dataset.
5. Evaluate and compare model performance.
6. Use the best-performing model for predictions.

## Results
- The models predict water potability with high accuracy.
- Feature importance analysis helps in understanding the key indicators affecting potability.

## Contribution
Contributions are welcome! Feel free to open issues and submit pull requests.

## License
This project is open-source and available under the [MIT License](LICENSE).

