# Price Data Analysis Project

This repository contains a project focused on analyzing and predicting price variations using machine learning techniques. The project is implemented in a Jupyter Notebook.

## Project Overview

The goal of this project is to analyze the provided price dataset, preprocess the data, build predictive models, and evaluate their performance. The notebook includes the following steps:

1. **Data Loading**: Importing the dataset and necessary libraries.
2. **Exploratory Data Analysis (EDA)**: Understanding the data through visualizations and summary statistics.
3. **Data Preprocessing**: Cleaning and transforming the data for model training.
4. **Model Building**: Training various machine learning models to predict price variations.
5. **Model Evaluation**: Evaluating the models' performance and selecting the best one.
6. **Prediction**: Using the trained model to make predictions on new data.

## Repository Structure

```
price-data-analysis/
│
├── data/
│   └── price_data.csv
│
├── notebooks/
│   └── price-data-analysis.ipynb
│
├── README.md
│
└── requirements.txt
```

- `data/`: Directory containing the dataset.
- `notebooks/`: Directory containing the Jupyter Notebook with the project implementation.
- `README.md`: This file, providing an overview of the project.
- `requirements.txt`: File listing the necessary Python packages to run the notebook.

## Installation

To run the notebook, you need to have Python installed. You can install the required packages using `pip`:

```bash
pip install -r requirements.txt
```

## Usage

Open the Jupyter Notebook and run the cells to execute the project steps. You can start the Jupyter Notebook server by running:

```bash
jupyter notebook
```

Navigate to the `notebooks/` directory and open `price-data-analysis.ipynb` to explore the project.

## Data

The dataset used in this project is included in the `data/` directory. It contains the following columns:

- `id`: Unique identifier for each entry.
- `price_date`: Date of the price record.
- `price_off_peak_var`: Off-peak variable price.
- `price_peak_var`: Peak variable price.
- `price_mid_peak_var`: Mid-peak variable price.
- `price_off_peak_fix`: Off-peak fixed price.
- `price_peak_fix`: Peak fixed price.
- `price_mid_peak_fix`: Mid-peak fixed price.
- `month`: Month of the price record.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgements

- Acknowledge any individuals or organizations that contributed to the project.
