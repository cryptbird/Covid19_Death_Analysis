# Covid19_Death_Analysis
```markdown
# COVID-19 Prediction for December 2021

Author: Khushvardhan Bhardwaj

## Introduction

This Python script is designed to predict COVID-19 statistics (total cases, active cases, and deaths) for December 2021 using Linear Regression. It processes historical COVID-19 data and leverages a linear regression model to make predictions.

## Getting Started

### Prerequisites

To run this script, you need to have the following prerequisites installed:

- Python 3
- pandas
- scikit-learn

You can install the required Python packages using pip:

```bash
pip install pandas scikit-learn
```

### Usage

1. Place your COVID-19 data in the specified format (e.g., in a CSV file) in the same directory as the script or provide the correct file path.

2. Modify the script to specify the data file's name or path, if necessary:

```python
data = pd.read_csv('covid_data.csv')
```

3. Run the Python script to predict COVID-19 statistics for December 2021:

```bash
python covid_prediction.py
```

4. The script will output the predicted total cases, active cases, and deaths for December 2021.

## Data Format

The script assumes that the COVID-19 data is provided in the following format:

| Sno | Date       | Time   | State/UnionTerritory          | ConfirmedIndianNational | ConfirmedForeignNational | Cured | Deaths | Confirmed |
|-----|------------|--------|-------------------------------|-------------------------|-------------------------|-------|--------|-----------|
| ... | ...        | ...    | ...                           | ...                     | ...                     | ...   | ...    | ...       |

Ensure that the 'Date' column is in the 'dd-mm-yyyy' format.

## Methodology

1. The script loads the COVID-19 data and preprocesses it, filtering data from March 2020 to August 2021.

2. It groups the data by date and calculates total cases, active cases, and deaths for each day.

3. Linear regression models are trained for total cases, active cases, and deaths using numerical date values as features.

4. The models are used to predict COVID-19 statistics for December 2021.




Feel free to reach out to the author, Khushvardhan Bhardwaj, with any questions or feedback.
```
